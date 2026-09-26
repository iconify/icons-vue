<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mps1_khmf"/><path class="wlo01od-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:captions-duotone" /></template>
<style>
.mps1_khmf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L19 3C21.20914 3 23 4.79086 23 7L23 17C23 19.20914 21.20914 21 19 21L5 21C2.79086 21 1 19.20914 1 17L1 7C1 4.79086 2.79086 3 5 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wlo01od-c {
  d: path("M10 10C9.5673 9.6754 9.0409 9.5 8.5 9.5C7.1193 9.5 6 10.6193 6 12C6 13.3807 7.1193 14.5 8.5 14.5C9.0409 14.5 9.5673 14.3246 10 14M18 10C17.5673 9.6754 17.0409 9.5 16.5 9.5C15.1193 9.5 14 10.6193 14 12C14 13.3807 15.1193 14.5 16.5 14.5C17.0409 14.5 17.5673 14.3246 18 14");
}

</style>
