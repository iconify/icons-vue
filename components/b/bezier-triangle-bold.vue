<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l44s8pbzo.css';
import '../../css/w/wh-sojvvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="l44s8pbzo"/><path class="wh-sojvvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-triangle-bold" /></template>
