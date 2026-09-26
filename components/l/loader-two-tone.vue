<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="thhjwpypo"/><path class="chylecb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:loader-two-tone" /></template>
<style>
.chylecb1o {
  d: path("M12 2V6M16.24264 7.75736L19.07107 4.92893M18 12H22M16.24264 16.24264L19.07107 19.07107");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.thhjwpypo {
  stroke-opacity: 0.4;
  d: path("M12 18V22M7.75736 16.24264L4.92893 19.07107M2 12H6M7.75736 7.75736L4.92893 4.92893");
}

</style>
