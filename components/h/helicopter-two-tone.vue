<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_otnib7b"/><path class="e4meqv80p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:helicopter-two-tone" /></template>
<style>
.e4meqv80p {
  d: path("M7 6L21 6M14 6L14 10M21.5207 14L16.5207 14M7 10L17.4793 10C18.5511 10 19.5414 10.5718 20.0773 11.5L21.6651 14.25C21.8845 14.63 22 15.0612 22 15.5C22 16.8807 20.8807 18 19.5 18L12.7735 18C12.059 18 11.3988 17.6188 11.0415 17L7 10ZM2 10L7 10M2 7L2 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_otnib7b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.2396 9L17.4793 9C18.9084 9 20.2288 9.7624 20.9433 11L22.5311 13.75C22.8383 14.2821 23 14.8857 23 15.5C23 17.433 21.433 19 19.5 19L12.7735 19C11.7017 19 10.7114 18.4282 10.1755 17.5L6.134 10.5C6.0462 10.348 6 10.1755 6 10C6 9.4477 6.4477 9 7 9Z");
  stroke: none;
}

</style>
