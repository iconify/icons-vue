<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-567abzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capital-city" /></template>
<style>
.e-567abzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 3.125zA1.206 1.206 0 0 0 13.41 4h.189a.273.273 0 0 1 .151.5a1.235 1.235 0 0 0-.502 1.367l.004.016a.331.331 0 0 1-.502.367a1.35 1.35 0 0 0-1.5 0a.331.331 0 0 1-.502-.367l.004-.016A1.235 1.235 0 0 0 10.25 4.5a.273.273 0 0 1 .151-.5h.189a1.206 1.206 0 0 0 1.16-.875a.26.26 0 0 1 .5 0M12 5.75V8m-4.5 4.5a4.5 4.5 0 0 1 9 0m-13 0h17m-17 9h17M7 12.5v9m5-9v9m5-9v9");
}

</style>
