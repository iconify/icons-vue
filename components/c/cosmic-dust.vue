<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h083wdb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cosmic-dust" /></template>
<style>
.h083wdb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3c.5 4.5 1.5 5.5 6 6c-4.5.5-5.5 1.5-6 6c-.5-4.5-1.5-5.5-6-6c4.5-.5 5.5-1.5 6-6m9 2h.01m1.49 7h.01m-5.01 5h.01M8 20h.01M20 19.5h.01");
}

</style>
