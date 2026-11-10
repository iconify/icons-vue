<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kuqcsgbye"/><path class="p71z5nh8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-arrow-up-duotone" /></template>
<style>
.kuqcsgbye {
  stroke-opacity: 0.4;
  d: path("M2 18.0007L3.7857 13.0007L6.0583 6.6676C6.3743 5.7827 7.6257 5.7827 7.9417 6.6676L10.2143 13.0007L12 18.0007M10.2143 13.0007H3.7857");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p71z5nh8n {
  d: path("M19 18V8M16 11L19 8L22 11");
}

</style>
