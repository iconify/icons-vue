<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2dl0sb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:landmark-nearby" /></template>
<style>
.q2dl0sb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.064 16.439l.417-10.223a1.5 1.5 0 0 1 .299-.839l.47-.627a.937.937 0 0 1 1.5 0l.47.627a1.5 1.5 0 0 1 .299.839l.417 10.223A1.5 1.5 0 0 1 12.438 18h-.876a1.5 1.5 0 0 1-1.498-1.561M4.5 21.5v-1.75h2.75V18h9.5v1.75h2.75v1.75Zm6-15.75h3");
}

</style>
