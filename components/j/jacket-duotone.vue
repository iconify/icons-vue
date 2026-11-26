<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pl6tyhhuz"/><path class="zlu6n3blh"/><path class="zq26643tr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:jacket-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pl6tyhhuz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.5745 10.9062L22.9586 17.5948C22.9862 17.7285 23 17.8642 23 18C23 19.1046 22.1046 20 21 20L18 20L18 20.5C18 21.8807 16.8807 23 15.5 23L8.5 23C7.1193 23 6 21.8807 6 20.5L6 20L3 20C1.8954 20 1 19.1046 1 18C1 17.8632 1.0141 17.7276 1.0415 17.5948L3.8096 4.2176C4.0081 3.2584 4.6623 2.4567 5.562 2.0697L7.6701 1.1627C7.9202 1.0551 8.1892 1 8.4605 1C9.272 1 10.0033 1.4904 10.3111 2.2416L12 6.3628L13.6889 2.2416C13.9967 1.4904 14.728 1 15.5395 1C15.8108 1 16.0798 1.0551 16.33 1.1627L18.4381 2.0697C19.3377 2.4567 19.9919 3.2584 20.1904 4.2176Z");
  stroke: none;
}

.zlu6n3blh {
  fill: currentColor;
  d: path("M11 23L11 22L11 7.3628L11 4.3628C11 4.2524 11.0179 4.1462 11.0509 4.0469L12 6.3628L12.9491 4.0469C12.9821 4.1462 13 4.2524 13 4.3628L13 7.3628L13 22L13 23Z");
  stroke: none;
}

.zq26643tr {
  d: path("M7 10L7 19M17 10L17 19");
}

</style>
