<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2syyxbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-move" /></template>
<style>
.t2syyxbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.75v12.5M2.75 9h12.5m-8.5-4L9 2.75L11.25 5m-4.5 8L9 15.25L11.25 13M5 6.75L2.75 9L5 11.25m8-4.5L15.25 9L13 11.25m1.68 3.06l5.89 2.63q.68.31-.03.56l-2.08.75q-.71.25-1.02.93l-.63 1.39q-.31.68-.55-.03l-2.02-5.83q-.24-.71.44-.4");
}

</style>
