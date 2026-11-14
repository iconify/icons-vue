<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brjih_byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:listening-exercise" /></template>
<style>
.brjih_byh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 14v-2a7.5 7.5 0 0 1 15 0v2M5.25 14za2.25 2.25 0 0 1 2.25 2.25v1.5A2.25 2.25 0 0 1 5.25 20A2.25 2.25 0 0 1 3 17.75v-1.5A2.25 2.25 0 0 1 5.25 14m13.5 0zA2.25 2.25 0 0 1 21 16.25v1.5A2.25 2.25 0 0 1 18.75 20a2.25 2.25 0 0 1-2.25-2.25v-1.5A2.25 2.25 0 0 1 18.75 14");
}

</style>
