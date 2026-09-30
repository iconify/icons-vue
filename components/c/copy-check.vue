<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z225yx37v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-check" /></template>
<style>
.z225yx37v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2L5 2C3.34315 2 2 3.34315 2 5L2 13C2 14.2714 2.8015 15.4046 4 15.8284M11 8L19 8C20.65684 8 22 9.34316 22 11L22 19C22 20.65684 20.65684 22 19 22L11 22C9.34316 22 8 20.65684 8 19L8 11C8 9.34316 9.34316 8 11 8ZM12 15L14 17L18 13");
}

</style>
