<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mj86nfbjt.css';
import '../../css/w/w9_t02b1j.css';
import '../../css/o/osqcjnb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="mj86nfbjt"/><path clip-rule="evenodd" class="w9_t02b1j"/><path class="osqcjnb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:headphones-bold" /></template>
