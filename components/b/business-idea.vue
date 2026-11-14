<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkao8rj2l"/><path class="gyss56t3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-idea" /></template>
<style>
.gyss56t3p {
  d: path("M12.5 9za1.5 1.5 0 0 1 1.5 1.5a.621.621 0 0 1-1.061.439l-.878-.878A.621.621 0 0 1 12.5 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkao8rj2l {
  d: path("M9 17.5c0-2-3.5-3.5-3.5-7.5a6.5 6.5 0 0 1 13 0c0 4-3.5 5.5-3.5 7.5Zm.5 3h5M10 13l4-4");
}

</style>
