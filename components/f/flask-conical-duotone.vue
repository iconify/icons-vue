<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d2s6l3b0f"/><path class="f46_rbcys"/><path class="vdv47vfaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-duotone" /></template>
<style>
.d2s6l3b0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.5 1L13.5 1C14.6046 1 15.5 1.8954 15.5 3L15.5 7.7741L20.7064 18.7105C20.8981 19.1133 20.9976 19.5539 20.9976 20C20.9976 21.6569 19.6545 23 17.9976 23L6.0024 23C4.3455 23 3.0024 21.6569 3.0024 20C3.0024 19.5539 3.1019 19.1133 3.2936 18.7105L8.5 7.7741L8.5 3C8.5 1.8954 9.3954 1 10.5 1Z");
  stroke: none;
}

.f46_rbcys {
  fill: currentColor;
  d: path("M4.1079 17L19.8921 17L20.7064 18.7105C20.8981 19.1133 20.9976 19.5539 20.9976 20C20.9976 21.6569 19.6545 23 17.9976 23L6.0024 23C4.3455 23 3.0024 21.6569 3.0024 20C3.0024 19.5539 3.1019 19.1133 3.2936 18.7105Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vdv47vfaw {
  d: path("M8 2L16 2");
}

</style>
