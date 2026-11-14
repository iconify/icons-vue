<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3os_bb6s"/><path class="t6opayz_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filtration" /></template>
<style>
.l3os_bb6s {
  d: path("M3.5 3.5h17l-7 7.5v3h-3v-3Z");
}

.t6opayz_b {
  d: path("M8 3.5L12 8l4-4.5m-4 13.25s-1.75 1.75-1.75 2.75a1.75 1.75 0 0 0 3.5 0c0-1-1.75-2.75-1.75-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
