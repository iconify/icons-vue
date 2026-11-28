<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sr00wfbbp"/><path class="yqjyynbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ease-in-out-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sr00wfbbp {
  d: path("M2.5 20.5L3.5 20.5C12 20.5 12 3.5 20.5 3.5L21.5 3.5");
}

.yqjyynbgt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3.5C5 4.3285 4.3285 5 3.5 5C2.6715 5 2 4.3285 2 3.5C2 2.6715 2.6715 2 3.5 2C4.3285 2 5 2.6715 5 3.5ZM10 3.5C10 4.3285 9.3285 5 8.5 5C7.6715 5 7 4.3285 7 3.5C7 2.6715 7.6715 2 8.5 2C9.3285 2 10 2.6715 10 3.5ZM17 20.5C17 21.3285 16.3285 22 15.5 22C14.6715 22 14 21.3285 14 20.5C14 19.6715 14.6715 19 15.5 19C16.3285 19 17 19.6715 17 20.5ZM22 20.5C22 21.3285 21.3285 22 20.5 22C19.6715 22 19 21.3285 19 20.5C19 19.6715 19.6715 19 20.5 19C21.3285 19 22 19.6715 22 20.5Z");
  stroke: none;
}

</style>
