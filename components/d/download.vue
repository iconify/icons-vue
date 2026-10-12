<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjjo9o4hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:download" /></template>
<style>
.vjjo9o4hl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.25v2.5a2.5 2.5 0 0 0 2.5 2.5h11.5a2.5 2.5 0 0 0 2.5-2.5v-2.5M12 3.75v11.5M7.75 11L12 15.25L16.25 11");
}

</style>
