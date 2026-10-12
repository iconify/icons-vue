<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxay34iau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barbed-wire" /></template>
<style>
.uxay34iau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7h18.5M2.75 17h18.5M4.5 5l4 4m0-4l-4 4m9-4l4 4m0-4l-4 4m-5 6l4 4m0-4l-4 4m7-4l4 4m0-4l-4 4");
}

</style>
