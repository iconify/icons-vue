<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8tys7bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitchen-timer" /></template>
<style>
.b8tys7bww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c4 0 7.25 6.25 7.25 11a7.25 7.25 0 0 1-14.5 0C4.75 9 8 2.75 12 2.75m-7.25 11h14.5M12 7.25v3m-3.5 6.5v1m3.5-1v1.5m3.5-1.5v1");
}

</style>
