<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjf5jwbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-studio" /></template>
<style>
.vjf5jwbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.5h10.5A1.75 1.75 0 0 1 19 5.25v7.5a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 12.75v-7.5A1.75 1.75 0 0 1 6.75 3.5m-4.25 11h19M12 2v1.5m-4 11l-2.5 7m10.5-7l2.5 7m-6.5-7v7");
}

</style>
