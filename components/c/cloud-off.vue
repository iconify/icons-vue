<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z991n9bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-off" /></template>
<style>
.z991n9bzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 18.35a4 4 0 0 1-.55-7.96A5.75 5.75 0 0 1 16.85 9a4.5 4.5 0 0 1-.6 9.35Zm-3-14.6l16.5 16.5");
}

</style>
