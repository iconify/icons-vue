<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n36iu814m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jumper-cables" /></template>
<style>
.n36iu814m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h3q1 0 1.07 1l.36 4.75q.07 1-.93 1h-4q-1 0-.93-1l.36-4.75q.07-1 1.07-1m1.5 0V6m11-3.25h3q1 0 1.07 1l.36 4.75q.07 1-.93 1h-4q-1 0-.93-1l.36-4.75q.07-1 1.07-1m1.5 0V6M5.75 9.5V16c0 2.75 2 5.25 5 5.25m7.5-11.75V16c0 2.75-2 5.25-5 5.25");
}

</style>
