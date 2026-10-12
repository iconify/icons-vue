<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owgo7fb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-freeze" /></template>
<style>
.owgo7fb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 18.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-8.5a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v4m-18.5-2.5h18.5M17.5 14v7m-3.03-5.25l6.06 3.5m-6.06 0l6.06-3.5");
}

</style>
