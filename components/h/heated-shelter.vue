<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nukscg80z"/><path class="u0-7g4ztn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heated-shelter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nukscg80z {
  d: path("m3 13.25l9-6.5l9 6.5");
}

.u0-7g4ztn {
  d: path("M5.5 11.5V21h13v-9.5m-11-4.25q-1-1.25 0-2.5t0-2.25m9 4.75q-1-1.25 0-2.5t0-2.25");
}

</style>
