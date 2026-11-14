<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0uu6ccdd"/><path class="sprrr0bru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fly-reel" /></template>
<style>
.e0uu6ccdd {
  d: path("M4 12.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sprrr0bru {
  d: path("M9 4.5v-2h6v2m-5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0M16 9h.01");
}

</style>
