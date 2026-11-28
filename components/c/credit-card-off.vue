<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exrzeobqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-off" /></template>
<style>
.exrzeobqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 9L9 9M14.6569 9L22 9M19.8715 19.8715C19.5957 19.9551 19.3031 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 7C2 5.6462 2.8967 4.5019 4.1285 4.1285M9.6569 4L19 4C20.6569 4 22 5.3431 22 7L22 16.3431M2 2L22 22");
}

</style>
