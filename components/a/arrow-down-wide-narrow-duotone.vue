<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ie7-rmbwb"/><path class="xz-w_6buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-wide-narrow-duotone" /></template>
<style>
.ie7-rmbwb {
  stroke-opacity: 0.4;
  d: path("M14 6L22 6M14 10L20 10M14 14L18 14M14 18L16 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xz-w_6buo {
  d: path("M6 6L6 18M2 14L5.6464 17.6464C5.8417 17.8417 6.1583 17.8417 6.3536 17.6464L10 14");
}

</style>
