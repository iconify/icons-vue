<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f0yusve5z"/><path class="e3qcjurvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-minus-duotone" /></template>
<style>
.e3qcjurvl {
  d: path("M2 12.625L11.5618 17.2864C11.7001 17.3538 11.85 17.3875 12 17.3875M2 17.2375L11.5618 21.8989C11.7001 21.9663 11.85 22 12 22M17 19.5L22 19.5");
}

.f0yusve5z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.6236 11.379L2.1236 9.1853C1.3759 8.8208 1 8.0942 1 7.3875C1 6.6808 1.3759 5.9542 2.1236 5.5897L11.1236 1.2022C11.6768 0.9326 12.3232 0.9326 12.8763 1.2022L21.8764 5.5897C22.6241 5.9542 23 6.6808 23 7.3875C23 8.0942 22.6241 8.8208 21.8764 9.1853L12.8764 13.5728C12.3232 13.8424 11.6768 13.8424 11.1237 13.5728Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
