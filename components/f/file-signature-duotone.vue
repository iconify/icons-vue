<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f_v42_b1n"/><path class="o0qwmfm8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-signature-duotone" /></template>
<style>
.f_v42_b1n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8L21 18C21 20.7614 18.7614 23 16 23L8 23C5.2386 23 3 20.7614 3 18L3 6C3 3.2386 5.2386 1 8 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0qwmfm8a {
  d: path("M20 8L14 2M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M8 13.7228C10.1818 13.2431 10.4242 11.324 10.6666 12.2835C10.9091 13.2431 11.3939 14.2026 12.1212 13.9627C12.8485 13.7228 13.0909 12.5234 13.5757 13.2431C14.0606 13.9627 15.2728 13.9627 16 13.9627M8 18L16 18");
}

</style>
