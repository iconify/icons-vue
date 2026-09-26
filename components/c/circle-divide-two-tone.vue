<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ox_05kl4h"/><path class="dygl0op_e"/><path class="sd8cfcjbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-divide-two-tone" /></template>
<style>
.dygl0op_e {
  d: path("M8 12L16 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox_05kl4h {
  d: path("M12 2C17.5228 2 22 6.4772 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2Z");
}

.sd8cfcjbo {
  fill: currentColor;
  d: path("M13.5 7.5C13.5 8.3284 12.8284 9 12 9C11.1716 9 10.5 8.3284 10.5 7.5C10.5 6.6716 11.1716 6 12 6C12.8284 6 13.5 6.6716 13.5 7.5ZM13.5 16.5C13.5 17.3284 12.8284 18 12 18C11.1716 18 10.5 17.3284 10.5 16.5C10.5 15.6716 11.1716 15 12 15C12.8284 15 13.5 15.6716 13.5 16.5Z");
  stroke: none;
}

</style>
