<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_otnib7b"/><path class="wvad3v5tf"/><path class="gy6l-w2-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:helicopter-duotone" /></template>
<style>
.gy6l-w2-f {
  d: path("M7 6L21 6M14 6L14 10M2 10L7 10M2 7L2 13");
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

.wvad3v5tf {
  fill: currentColor;
  d: path("M22.9641 15L21.5207 15L16.5207 15C15.9684 15 15.5207 14.5523 15.5207 14C15.5207 13.4477 15.9684 13 16.5207 13L21.5207 13L22.0981 13L22.5311 13.75C22.7543 14.1367 22.9008 14.5611 22.9641 15Z");
  stroke: none;
}

</style>
