<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y78ntvy6k"/><path class="n_sfw9rfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-click-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n_sfw9rfc {
  d: path("M11.4668 6.4688L14.6629 3.281M8.1994 5.6447L6.7529 1.317M5.6529 8.1826L1.3155 6.7405M6.4806 11.4418L3.2845 14.6296M8.9737 8.9553L13.4001 22L16.4918 16.2705L22 13.6016L8.9737 8.9553Z");
}

.y78ntvy6k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.0143 21.6534L9.27 9.8862C9.1468 9.499 9.5162 9.136 9.9026 9.2647L21.6597 13.1814C22.0965 13.3269 22.1184 13.9348 21.6933 14.1113L16.6698 16.1966C16.5552 16.2442 16.4625 16.3328 16.41 16.4449L13.9403 21.7135C13.7482 22.1234 13.1515 22.0847 13.0143 21.6534Z");
  stroke: none;
}

</style>
