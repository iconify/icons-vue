<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0qkgqd_a"/><path class="kxbgb37se"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cabin-fire" /></template>
<style>
.kxbgb37se {
  d: path("M9.75 16a2.5 2.5 0 0 1-2.5-2.5c0-1 .5-1.75 1-2.25c.25.75.5 1.25 1 1.25c0-1.5.25-3 1.25-4.5c0 2 1.75 3.25 1.75 5.5a2.5 2.5 0 0 1-2.5 2.5ZM18 14.75v3.5M18 21h.01");
}

.q0qkgqd_a {
  d: path("M7.75 3h4A3.25 3.25 0 0 1 15 6.25v11a3.25 3.25 0 0 1-3.25 3.25h-4a3.25 3.25 0 0 1-3.25-3.25v-11A3.25 3.25 0 0 1 7.75 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
