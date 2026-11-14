<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqef58bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alert-triangle" /></template>
<style>
.dqef58bex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.528 5.734l6.517 11.662A1.75 1.75 0 0 1 18.517 20H5.483a1.75 1.75 0 0 1-1.528-2.604l6.517-11.662a1.75 1.75 0 0 1 3.056 0M12 9.5v4.25m0 3h.01");
}

</style>
