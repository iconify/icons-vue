<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgchd8fvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fence" /></template>
<style>
.kgchd8fvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 7l1.5-3l1.5 3v14.25h-3Zm7.75 0L12 4l1.5 3v14.25h-3Zm7.75 0l1.5-3l1.5 3v14.25h-3Zm-15.5 3.25h18.5M2.75 16.5h18.5");
}

</style>
