<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fe4pabiai"/><path class="u19s2tbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card-duotone" /></template>
<style>
.fe4pabiai {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L19 3C21.2091 3 23 4.7909 23 7L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 7C1 4.7909 2.7909 3 5 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u19s2tbby {
  d: path("M11 10C11 11.1046 10.1046 12 9 12C7.8954 12 7 11.1046 7 10C7 8.8954 7.8954 8 9 8C10.1046 8 11 8.8954 11 10ZM5 20C5 17.7909 6.7909 16 9 16C11.2091 16 13 17.7909 13 20M15 10L18 10M15 14L18 14");
}

</style>
