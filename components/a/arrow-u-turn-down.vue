<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qvqfx6bxa"/><path class="u1xhjcsrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-u-turn-down" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvqfx6bxa {
  d: path("M18.5 20.25v-11a4.75 4.75 0 0 0-9.5 0v10.5");
}

.u1xhjcsrw {
  d: path("M12.5 16.25L9 19.75l-3.5-3.5");
}

</style>
