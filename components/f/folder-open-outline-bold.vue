<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m6u_t4bqm"/><path class="y5jslcbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-open-outline-bold" /></template>
<style>
.m6u_t4bqm {
  d: path("M4 20V4h5l3 3h7v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y5jslcbiw {
  d: path("m4 20 8 -8h10l-8 8Z");
}

</style>
