<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r391zzbqg"/><path clip-rule="evenodd" class="vpcb-kbtv"/><path class="qml68xbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyboard-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qml68xbxn {
  d: path("M19.872 19.8715C19.596 19.9551 19.303 20 19 20H5C3.343 20 2 18.6569 2 17V7C2 5.6462 2.897 4.5019 4.128 4.1285M8 16H16M2 2L22 22");
}

.r391zzbqg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.646 20.6465C20.129 20.8803 19.568 21.0008 19 21H5C2.791 21 1 19.2091 1 17V7C1 5.4276 1.921 4.0009 3.353 3.3535L20.646 20.6465ZM9.657 3H19C21.209 3 23 4.7909 23 7V16.3431H22.98C22.98 16.8844 22.542 17.3233 22 17.3233C21.74 17.3233 21.491 17.22 21.307 17.0361L21.293 17.0503L8.95 4.7071L8.964 4.6929C8.78 4.5092 8.677 4.2598 8.677 3.9998C8.677 3.4585 9.116 3.0198 9.657 3.02V3Z");
  stroke: none;
}

.vpcb-kbtv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 11H6.5C6.776 11 7 11.2239 7 11.5V12.5C7 12.7761 6.776 13 6.5 13H5.5C5.224 13 5 12.7761 5 12.5V11.5C5 11.2239 5.224 11 5.5 11Z");
  stroke: none;
}

</style>
