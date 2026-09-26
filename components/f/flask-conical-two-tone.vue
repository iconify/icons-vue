<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d2s6l3b0f"/><path class="e8_1crbxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-two-tone" /></template>
<style>
.d2s6l3b0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.5 1L13.5 1C14.6046 1 15.5 1.8954 15.5 3L15.5 7.7741L20.7064 18.7105C20.8981 19.1133 20.9976 19.5539 20.9976 20C20.9976 21.6569 19.6545 23 17.9976 23L6.0024 23C4.3455 23 3.0024 21.6569 3.0024 20C3.0024 19.5539 3.1019 19.1133 3.2936 18.7105L8.5 7.7741L8.5 3C8.5 1.8954 9.3954 1 10.5 1Z");
  stroke: none;
}

.e8_1crbxs {
  d: path("M10.5 2L13.5 2C14.0523 2 14.5 2.4477 14.5 3L14.5 7.7741C14.5 7.9228 14.5332 8.0697 14.5971 8.204L19.8035 19.1403C20.4353 20.4675 19.4675 22 17.9976 22L6.0024 22C4.5325 22 3.5647 20.4675 4.1965 19.1403L9.4029 8.204C9.4668 8.0697 9.5 7.9228 9.5 7.7741L9.5 3C9.5 2.4477 9.9477 2 10.5 2ZM8 2L16 2M4.7394 18L19.2606 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
