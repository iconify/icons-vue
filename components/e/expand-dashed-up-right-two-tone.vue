<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sz4fkkbjn"/><path class="mf2xnlsvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-two-tone" /></template>
<style>
.mf2xnlsvd {
  stroke-opacity: 0.4;
  d: path("M13 3L14.3333 3M18.3333 3C19.8061 3 21 4.1939 21 5.6667M21 9.6667L21 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sz4fkkbjn {
  d: path("M11 18L21 18M18 21L21 18L18 15M6 13L6 3M9 6L6 3L3 6");
}

</style>
