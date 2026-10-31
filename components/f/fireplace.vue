<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f8gezv97u.css';
import '../../css/x/x3cbt25_s.css';
import '../../css/i/irszdrruk.css';
import '../../css/l/l2jpnxw8r.css';
import '../../css/h/h9hwb0bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f8gezv97u wm-k"/><path class="wm-deco x3cbt25_s"/><path class="irszdrruk wm-k"/><path class="l2jpnxw8r wm-shadow"/><path class="h9hwb0bkv wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:fireplace" /></template>
