<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lvelce22s"/><path class="ix4g69x0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grill-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ix4g69x0x {
  d: path("M5.5 6L3 6C3 10.9706 7.0294 15 12 15C16.9706 15 21 10.9706 21 6L18.5 6M7 20C7 21.1046 6.1046 22 5 22C3.8954 22 3 21.1046 3 20C3 18.8954 3.8954 18 5 18C6.1046 18 7 18.8954 7 20ZM5.9923 18.2635L8.3094 14.2085M15 14.4853L18.2512 22.6292M7 20L17.2016 20M8.5 10L8.5 8.8028C8.5 7.6273 8.848 6.4781 9.5 5.5C10.1521 4.5219 10.5 3.3727 10.5 2.1972L10.5 1M13.5 10L13.5 8.8028C13.5 7.6273 13.848 6.4781 14.5 5.5C15.1521 4.5219 15.5 3.3727 15.5 2.1972L15.5 1");
}

.lvelce22s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.5 5L21 5C21.5523 5 22 5.4477 22 6C22.003 8.8305 20.8035 11.5291 18.7003 13.4235C16.8644 15.0847 14.4759 16.0032 12 16C9.1695 16.003 6.4709 14.8035 4.5765 12.7003C2.9153 10.8644 1.9968 8.4759 2 6C2 5.4477 2.4477 5 3 5L5.5 5Z");
  stroke: none;
}

</style>
