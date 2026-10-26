<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="wt_8-9b4y"/><path class="sg3s0jkvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:construction-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sg3s0jkvp {
  d: path("M6 11L6 20M18 11L18 20M4 20L8 20M16 20L20 20");
}

.wt_8-9b4y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 3L20 3C21.6569 3 23 4.3431 23 6L23 9C23 10.6569 21.6569 12 20 12L4 12C2.3431 12 1 10.6569 1 9L1 6C1 4.3431 2.3431 3 4 3ZM5.0858 10L7.9142 10L12.9142 5L10.0858 5L5.0858 10ZM11.0858 10L13.9142 10L18.9142 5L16.0858 5L11.0858 10Z");
  stroke: none;
}

</style>
