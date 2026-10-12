<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjpro05ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dutch-oven" /></template>
<style>
.jjpro05ja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5v-2m-6.5 5a6.5 3 0 0 1 13 0Zm0 2.5h13v3.5a4 4 0 0 1-4 4h-5a4 4 0 0 1-4-4Zm0 2.25h-2m15 0h2");
}

</style>
