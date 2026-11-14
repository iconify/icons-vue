<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrj57horr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanger-wooden" /></template>
<style>
.lrj57horr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5a2 2 0 1 0-2-2m2 3v.159a1.75 1.75 0 0 1-.657 1.366L8.25 11.5a1.685 1.685 0 0 0 1.052 3h5.396a1.685 1.685 0 0 0 1.052-3l-3.093-2.475A1.75 1.75 0 0 1 12 7.659zm-5.5 7h11a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

</style>
