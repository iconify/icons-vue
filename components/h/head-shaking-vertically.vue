<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gqmsfeblw.css';
import '../../css/c/czh7avbpl.css';
import '../../css/l/lv0a6gbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="gqmsfeblw"/><path class="czh7avbpl"/><path class="lv0a6gbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:head-shaking-vertically" /></template>
