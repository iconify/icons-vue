<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxlaqhbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-width-sharp" /></template>
<style>
.mxlaqhbbp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20ZM6 12L18 12M9.2929 8.7071L6 12L9.2929 15.2929M14.7071 8.7071L18 12L14.7071 15.2929");
}

</style>
