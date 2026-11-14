<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chnu4qvpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commodity-gold" /></template>
<style>
.chnu4qvpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.295 18.456l.583-1.5A1.5 1.5 0 0 1 5.276 16h3.448a1.5 1.5 0 0 1 1.398.956l.583 1.5A1.5 1.5 0 0 1 9.307 20.5H4.693a1.5 1.5 0 0 1-1.398-2.044m10 0l.583-1.5A1.5 1.5 0 0 1 15.276 16h3.448a1.5 1.5 0 0 1 1.398.956l.583 1.5a1.5 1.5 0 0 1-1.398 2.044h-4.614a1.5 1.5 0 0 1-1.398-2.044m-5-7.25l.583-1.5a1.5 1.5 0 0 1 1.398-.956h3.448a1.5 1.5 0 0 1 1.398.956l.583 1.5a1.5 1.5 0 0 1-1.398 2.044H9.693a1.5 1.5 0 0 1-1.398-2.044M12 3v2.5m-5-1L8.5 6M17 4.5L15.5 6");
}

</style>
