function get_mtime() {
    $mtime = get_the_modified_time('Ymd');
    $ptime = get_the_time('Ymd');
    if ($ptime > $mtime) {
        return get_the_time();
    } elseif ($ptime === $mtime) {
        return null;
    } else {
        return get_the_modified_time();
    }
}
