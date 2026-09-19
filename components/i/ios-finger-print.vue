<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq320zf_x.css';
import '../../css/t/t9j2repmk.css';
import '../../css/c/c9-klwxag.css';
import '../../css/t/tey_ov27w.css';
import '../../css/h/h2-6m2w-z.css';
import '../../css/s/skn-k9yba.css';
import '../../css/b/bw4xunb6i.css';
import '../../css/a/ao8w-3b5l.css';
import '../../css/f/f6xagccdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq320zf_x"/><path class="t9j2repmk"/><path class="c9-klwxag"/><path class="tey_ov27w"/><path class="h2-6m2w-z"/><path class="skn-k9yba"/><path class="bw4xunb6i"/><path class="ao8w-3b5l"/><path class="f6xagccdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-finger-print" /></template>
