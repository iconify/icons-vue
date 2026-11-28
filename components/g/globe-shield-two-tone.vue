<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jhcgq_flp"/><path class="pfv0j71em"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-shield-two-tone" /></template>
<style>
.jhcgq_flp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.3216 1 21.76 4.7791 22.7793 9.7998C22.7923 9.8642 22.7998 9.9317 22.7998 10C22.7998 10.5523 22.352 11 21.7998 11L14 11C12.3431 11 11 12.3431 11 14L11 21.7998C11 22.352 10.5523 22.7998 10 22.7998C9.9317 22.7998 9.8652 22.7923 9.8008 22.7793C4.78 21.76 1 17.3216 1 12C1 5.9249 5.9249 1 12 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfv0j71em {
  d: path("M10 21.8C5.4355 20.8734 2 16.8379 2 12C2 6.4772 6.4772 2 12 2C16.8379 2 20.8734 5.4355 21.8 10M2 12L10 12M9 17.2271C8.3333 15.5 8 13.75 8 12C8 8.5 9.3333 5 12 2C14.1579 4.4276 15.4426 7.1826 15.8544 10M15.5173 15.3862C16.6758 15.2487 17.5504 14.6703 18.0731 14.1633C18.2974 13.9456 18.7026 13.9456 18.9269 14.1633C19.4496 14.6703 20.3242 15.2487 21.4827 15.3862C21.7669 15.4199 22 15.6409 22 15.9175L22 17.8747C22 18.651 21.8736 19.4412 21.3928 20.0631C20.8667 20.7434 20.0327 21.5058 18.863 21.9355C18.6288 22.0215 18.3712 22.0215 18.137 21.9355C16.9673 21.5058 16.1332 20.7434 15.6073 20.0631C15.1264 19.4412 15 18.651 15 17.8747L15 15.9175C15 15.6409 15.2331 15.4199 15.5173 15.3862Z");
}

</style>
