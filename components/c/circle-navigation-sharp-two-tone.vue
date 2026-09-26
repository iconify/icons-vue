<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o7x5x1gvm"/><path class="gy4hwzihc"/><path class="tq4hd5byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-navigation-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gy4hwzihc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.0423 20.515L11.1255 11.3505C11.5063 10.6638 12.4937 10.6638 12.8745 11.3505L17.9577 20.515C18.3669 21.2526 17.735 22.1343 16.905 21.984L12 21.0957L7.095 21.984C6.265 22.1343 5.6331 21.2526 6.0423 20.515Z");
  stroke: none;
}

.o7x5x1gvm {
  d: path("M19.4 19.8L20 19C21.2982 17.269 22 15.1637 22 13C22 7.4771 17.5229 3 12 3C6.4771 3 2 7.4771 2 13C2 15.1637 2.7018 17.269 4 19L4.6 19.8");
}

.tq4hd5byh {
  d: path("M6.9168 21L12 11.8355L17.0832 21L12 20.0794L6.9168 21Z");
}

</style>
