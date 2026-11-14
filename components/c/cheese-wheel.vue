<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_-_jdb5z"/><path class="qmdwc8miz"/><path class="u80ssxhzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheese-wheel" /></template>
<style>
.e_-_jdb5z {
  d: path("M12 9h8.5a8.5 3.5 0 1 0-5.5 3.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmdwc8miz {
  d: path("M3.5 9v6A8.5 3.5 0 0 0 15 18.25v-6");
}

.u80ssxhzl {
  d: path("M20.5 9v6H12V9m0 6l3 3.25");
}

</style>
