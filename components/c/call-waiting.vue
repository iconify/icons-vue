<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zttm14a3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-waiting" /></template>
<style>
.zttm14a3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.6 3.25h2.6a1 1 0 0 1 .95.68l1.1 3.3A1 1 0 0 1 10 8.25l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6a1 1 0 0 1 1.02-.25l3.3 1.1a1 1 0 0 1 .68.95v2.6a2.35 2.35 0 0 1-2.35 2.35c-8.3 0-15.15-6.85-15.15-15.15A2.35 2.35 0 0 1 5.6 3.25m9.9-.5h5m-5 7.5h5m-4.25-7.5V4c0 .8.4 1.55 1.05 2l.7.5l.7.5c.65.45 1.05 1.2 1.05 2v1.25m0-7.5V4c0 .8-.4 1.55-1.05 2l-.7.5l-.7.5c-.65.45-1.05 1.2-1.05 2v1.25");
}

</style>
