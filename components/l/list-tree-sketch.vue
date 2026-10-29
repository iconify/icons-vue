<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c3brbdctz.css';
import '../../css/p/pgmcs8b1q.css';
import '../../css/x/xw4rj9ggz.css';
import '../../css/q/qzys12byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c3brbdctz wm-k"/><path class="pgmcs8b1q wm-a"/><path class="wm-k xw4rj9ggz"/><path class="qzys12byp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-tree-sketch" /></template>
