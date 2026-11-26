<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r9qos6bhp"/><path class="i4bb1ab-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:avocado-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i4bb1ab-h {
  d: path("M18.1987 2.0004C19.211 1.9866 20.1857 2.3826 20.9016 3.0985C21.6174 3.8143 22.0135 4.7892 21.9996 5.8015C21.9355 10.4894 20.0446 14.9675 16.7293 18.2827C15.7344 19.2776 14.6263 20.1524 13.4278 20.8892C10.4703 22.7072 6.6516 22.2579 4.1968 19.8032C1.7421 17.3484 1.2928 13.5297 3.1108 10.5722C3.8476 9.3738 4.7224 8.2657 5.7172 7.2708C9.0325 3.9556 13.5106 2.0646 18.1987 2.0004ZM11.6214 16.6212C10.4498 17.7928 8.5504 17.7928 7.3788 16.6212C6.2072 15.4496 6.2072 13.5502 7.3788 12.3786C8.5504 11.207 10.4498 11.207 11.6214 12.3786C12.793 13.5502 12.793 15.4496 11.6214 16.6212Z");
}

.r9qos6bhp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.0541 2.4952C13.2918 1.5504 15.7107 1.0344 18.185 1.0005C19.4673 0.983 20.7019 1.4846 21.6087 2.3914C22.5154 3.2981 23.0171 4.5329 22.9995 5.8152C22.9318 10.7635 20.9359 15.4904 17.4364 18.9898C16.3862 20.04 15.2166 20.9634 13.9515 21.7411C10.5996 23.8015 6.2718 23.2923 3.4897 20.5103C0.7077 17.7282 0.1985 13.4004 2.2589 10.0485C3.0366 8.7835 3.96 7.6139 5.0101 6.5637C6.7598 4.814 8.8165 3.4401 11.0541 2.4952Z");
  stroke: none;
}

</style>
