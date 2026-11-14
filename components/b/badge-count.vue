<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s2cegh51x"/><path class="vxyakx64c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-count" /></template>
<style>
.s2cegh51x {
  d: path("M5.5 7h13a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxyakx64c {
  d: path("m8 10.5l1.5-1.25v5.5M15 9.5v5M12.5 12h5");
}

</style>
