<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="eb9xdy2pm"/><path class="cm2-hcc9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-3-vertical-sharp-two-tone" /></template>
<style>
.cm2-hcc9z {
  d: path("M5 22L5 2M1.7071 18.7071L5 22L8.2929 18.7071M1.7071 5.2929L5 2L8.2929 5.2929M11 14L22 14L22 22ZM11 10L22 10L22 2Z");
}

.eb9xdy2pm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 13L22 13C22.5523 13 23 13.4477 23 14L23 22C23 22.5523 22.5523 23 22 23C21.7887 23 21.5827 22.933 21.4118 22.8087L10.4118 14.8087C10.1531 14.6206 10 14.3199 10 14C10 13.4477 10.4477 13 11 13ZM11 11C10.4477 11 10 10.5523 10 10C10 9.6801 10.1531 9.3794 10.4118 9.1913L21.4118 1.1913C21.5827 1.067 21.7887 1 22 1C22.5523 1 23 1.4477 23 2L23 10C23 10.5523 22.5523 11 22 11L11 11Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
