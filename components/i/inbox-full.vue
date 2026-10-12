<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ku4hbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inbox-full" /></template>
<style>
.z5ku4hbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.75h4.4l1.1 2.2c.25.5.75.8 1.3.8h4.9c.55 0 1.05-.3 1.3-.8l1.1-2.2h4.4v3a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Zm0 0l1.6-4.5A2 2 0 0 1 6.25 9h1m14 5.75l-1.6-4.5A2 2 0 0 0 17.75 9h-1m-9 2.75h8.5m-7.5-3.5h6.5m-5.5-3.5h4.5");
}

</style>
