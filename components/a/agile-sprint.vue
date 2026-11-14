<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ntlbqn9_t"/><path class="bihy412yv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agile-sprint" /></template>
<style>
.bihy412yv {
  fill: currentColor;
  d: path("M4.5 3.5h3.75v3.75H4.5Zm7.5 0h3.75v3.75H12ZM8.25 7.25H12V11H8.25Zm7.5 0h3.75V11h-3.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntlbqn9_t {
  d: path("M4.5 2.5v19M6 3.5h12A1.5 1.5 0 0 1 19.5 5v4.5A1.5 1.5 0 0 1 18 11H6a1.5 1.5 0 0 1-1.5-1.5V5A1.5 1.5 0 0 1 6 3.5");
}

</style>
