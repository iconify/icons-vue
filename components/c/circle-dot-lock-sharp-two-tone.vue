<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kaf9h-50z"/><path class="fft-ax91h"/><path clip-rule="evenodd" class="gcrij3bes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dot-lock-sharp-two-tone" /></template>
<style>
.fft-ax91h {
  d: path("M12 22C11.666 22 11.3323 21.9833 11 21.9499C5.8901 21.4363 2 17.1356 2 12C2 6.4772 6.4772 2 12 2C16.3672 2 20.2292 4.834 21.5394 9C21.62 9.2564 21.6903 9.5157 21.75 9.7778M15 17L22 17L22 22L15 22ZM16.5 17L16.5 15C16.5 13.8954 17.3954 13 18.5 13C19.6046 13 20.5 13.8954 20.5 15L20.5 17");
}

.gcrij3bes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kaf9h-50z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C17.2348 1 21.6155 4.6567 22.7273 9.555L20.775 10L12 10Z");
  stroke: none;
}

</style>
