<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bbvxd2mjs"/><path class="pg0en1bcd"/><path class="qoxqdyb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:label-review-outline-bold" /></template>
<style>
.bbvxd2mjs {
  d: path("M3 6h10l3.5 3.5L13 13H3Z");
}

.pg0en1bcd {
  d: path("M13 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qoxqdyb0z {
  d: path("m18.5 19.5 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
