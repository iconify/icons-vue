<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rce4qsbht"/><path class="guu8zvb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:container-two-tone" /></template>
<style>
.guu8zvb_l {
  d: path("M2 11C2 9.8954 2.8954 9 4 9L16 9C17.1046 9 18 9.8954 18 11L18 17C18 18.1046 17.1046 19 16 19L4 19C2.8954 19 2 18.1046 2 17L2 11ZM2.5858 9.5858L6.5858 5.5858C6.9609 5.2107 7.4696 5 8 5L20 5C21.1046 5 22 5.8954 22 7L22 13C22 13.5304 21.7893 14.0391 21.4142 14.4142L17.4142 18.4142M17.4142 9.5858L21.4142 5.5858M6 9L6 19M10 9L10 19M14 9L14 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rce4qsbht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 20C2.3431 20 1 18.6569 1 17L1 11C1 10.2044 1.3161 9.4413 1.8787 8.8787L5.8787 4.8787C6.4413 4.3161 7.2044 4 8 4L20 4C21.6569 4 23 5.3431 23 7L23 13C23 13.7956 22.6839 14.5587 22.1213 15.1213L18.1213 19.1213C17.5587 19.6839 16.7956 20 16 20L4 20Z");
  stroke: none;
}

</style>
