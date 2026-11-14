<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7vlc6biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gyoji-fan" /></template>
<style>
.j7vlc6biq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17L2.75 7.75a13 13 0 0 1 18.5 0Zm-1.5-5.5l-1.75-7m4.75 7l1.75-7M12 17v4");
}

</style>
