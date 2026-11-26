<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wkoda7aty"/><path class="t88efyb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:aperture-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t88efyb6i {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2ZM16.3301 9.5L6.3588 3.7431M16.3301 14.5L16.3301 2.9861M12 17L21.9713 11.2431M7.6699 14.5L17.6412 20.2569M7.6699 9.5L7.6699 21.0139M12 7L2.0287 12.7569");
}

.wkoda7aty {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.2218 4.2218C6.2113 2.2323 8.9627 1 12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 8.9627 2.2323 6.2113 4.2218 4.2218Z");
  stroke: none;
}

</style>
