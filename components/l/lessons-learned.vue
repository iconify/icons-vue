<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xui0ngdhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lessons-learned" /></template>
<style>
.xui0ngdhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16c-2.5-1.25-6-1.75-9.5-1.5V20c3.5-.25 7 .25 9.5 1.5c2.5-1.25 6-1.75 9.5-1.5v-5.5c-3.5-.25-7 .25-9.5 1.5m0 0v5.5M10.25 10c-1.75-1-2.5-2.5-2.5-3.75a4.25 4.25 0 0 1 8.5 0c0 1.25-.75 2.75-2.5 3.75v.5h-3.5Zm.25 3h3");
}

</style>
