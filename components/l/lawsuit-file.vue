<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-82bcbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lawsuit-file" /></template>
<style>
.m8-82bcbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75a2 2 0 0 1 2-2h4l2 2.25h8.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Zm8 4.5l3.5 3.5M12.5 9.5L16 13m-2.75-1l-5 5");
}

</style>
