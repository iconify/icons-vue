<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqwo1bbye"/><path class="gx16_8b2j"/><path class="v-jogvb5z"/><path class="l9-vpjbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-check-duotone-regular" /></template>
<style>
.gx16_8b2j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 14 2.5 2.5L20 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9-vpjbes {
  d: path("m13 14 2.5 2.5L20 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sqwo1bbye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
