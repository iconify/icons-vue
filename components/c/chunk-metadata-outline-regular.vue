<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="pty_wsbvs"/><path class="ilth2b2qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunk-metadata-outline-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ilth2b2qd {
  d: path("M9 12h3l3 3 -3 3H9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pty_wsbvs {
  d: path("M8 9h8");
}

</style>
