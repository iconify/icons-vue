<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bp-skte0x.css';
import '../../css/w/w315tgbyz.css';
import '../../css/k/kb36qtbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="bp-skte0x"/><path class="w315tgbyz"/><path class="kb36qtbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bookmark-tabs" /></template>
