<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7y9_gy1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curtains" /></template>
<style>
.z7y9_gy1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19m-18 0v17h5C8.5 17 6 15 6 13c0-3 4.5-6 4.5-9.5m10 0v17h-5C15.5 17 18 15 18 13c0-3-4.5-6-4.5-9.5");
}

</style>
