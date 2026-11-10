<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kuqcsgbye"/><path class="kwf55hbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-text-cursor-duotone" /></template>
<style>
.kuqcsgbye {
  stroke-opacity: 0.4;
  d: path("M2 18.0007L3.7857 13.0007L6.0583 6.6676C6.3743 5.7827 7.6257 5.7827 7.9417 6.6676L10.2143 13.0007L12 18.0007M10.2143 13.0007H3.7857");
}

.kwf55hbal {
  d: path("M19 6.8C18.6667 6.35 17.6 5 16 5M19 6.8C19.3333 6.35 20.4 5 22 5M19 6.8V17.2M19 17.2C19.3333 17.65 20.4 19 22 19M19 17.2C18.6667 17.65 17.6 19 16 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
