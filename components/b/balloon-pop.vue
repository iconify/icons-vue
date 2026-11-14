<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cqv2lgpqn"/><path class="xg3nzcvav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-pop" /></template>
<style>
.cqv2lgpqn {
  d: path("M7 9a5 6.5 0 1 0 10 0A5 6.5 0 1 0 7 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg3nzcvav {
  d: path("m12 15.5l1 1.5h-2Zm0 1.5c-1.25 1.75 1.25 3 0 4.75M7 9.5l2.5-2L12 11l2.5-3.5l2.5 2M3 4.75L5.5 3.5l-.25 3Zm18 0L18.5 3.5l.25 3Z");
}

</style>
