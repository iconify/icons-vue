<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy11j83on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-arrow-up-fill" /></template>
<style>
.qy11j83on {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 18.0007L3.7857 13.0007L6.0583 6.6676C6.3743 5.7827 7.6257 5.7827 7.9417 6.6676L10.2143 13.0007L12 18.0007M10.2143 13.0007H3.7857M19 18.0007V8.0007M16 11.0007L19 8.0007L22 11.0007");
}

</style>
