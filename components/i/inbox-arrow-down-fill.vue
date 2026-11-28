<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="nmy17e9_c"/><path class="r5fbq5brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-down-fill" /></template>
<style>
.nmy17e9_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 13H8L10 16H14L16 13H22V17C22 18.6569 20.6569 20 19 20H5C3.3431 20 2 18.6569 2 17V13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5fbq5brl {
  d: path("M18.8952 7.0905L21.5574 11.4317C21.8468 11.9036 22 12.4464 22 13M22 13V17C22 18.6569 20.6569 20 19 20H5C3.3431 20 2 18.6569 2 17V13M22 13H16L14 16H10L8 13H2M2 13C2 12.4464 2.1532 11.9036 2.4426 11.4317L5.1048 7.0905M12 4V11M15 8L12 11L9 8");
}

</style>
