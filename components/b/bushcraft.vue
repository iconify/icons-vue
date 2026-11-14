<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyf3a_39x"/><path class="nyicw6bfb"/><path class="putab1e9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bushcraft" /></template>
<style>
.fyf3a_39x {
  d: path("m4.367 8.492l4.347-1.164a1.5 1.5 0 0 1 1.837 1.06a1.5 1.5 0 0 1-1.061 1.837L5.144 11.39a1.5 1.5 0 0 1-1.837-1.061a1.5 1.5 0 0 1 1.06-1.837");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyicw6bfb {
  d: path("m11.482 6.068l6.303-1.689a1.025 1.025 0 0 1 1.153 1.503l-.927 1.605a1.5 1.5 0 0 1-.91.699l-4.713 1.263a1.5 1.5 0 0 1-1.837-1.061l-.129-.483a1.5 1.5 0 0 1 1.06-1.837M6 15.25h12.5a2.5 3 0 0 1 0 6H6");
}

.putab1e9h {
  d: path("M3.5 18.25a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0m2.5 0h.01");
}

</style>
