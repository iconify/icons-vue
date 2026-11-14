<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fms9jlb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hinge" /></template>
<style>
.fms9jlb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 4h3.5a1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 8.75 20h-3.5a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 5.25 4m10 0h3.5a1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 18.75 20h-3.5a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 15.25 4M12 3za1.5 1.5 0 0 1 1.5 1.5v15A1.5 1.5 0 0 1 12 21a1.5 1.5 0 0 1-1.5-1.5v-15A1.5 1.5 0 0 1 12 3M6.75 7.5h.01m-.01 9h.01m10.49-9h.01m-.01 9h.01");
}

</style>
