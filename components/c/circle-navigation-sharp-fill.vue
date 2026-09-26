<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o7x5x1gvm"/><path class="aggi1x_pz"/><path class="tq4hd5byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-navigation-sharp-fill" /></template>
<style>
.aggi1x_pz {
  fill: currentColor;
  d: path("M6.9168 21L12 11.8355L17.0832 21L12 20.0794L6.9168 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7x5x1gvm {
  d: path("M19.4 19.8L20 19C21.2982 17.269 22 15.1637 22 13C22 7.4771 17.5229 3 12 3C6.4771 3 2 7.4771 2 13C2 15.1637 2.7018 17.269 4 19L4.6 19.8");
}

.tq4hd5byh {
  d: path("M6.9168 21L12 11.8355L17.0832 21L12 20.0794L6.9168 21Z");
}

</style>
