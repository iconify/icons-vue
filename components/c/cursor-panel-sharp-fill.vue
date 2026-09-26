<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fuchy-bvl"/><path class="tef3mjick"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-panel-sharp-fill" /></template>
<style>
.fuchy-bvl {
  fill: currentColor;
  d: path("M10.8295 11.4097L13.7772 20.6718C13.9071 21.0802 14.4723 21.1169 14.6542 20.7287L16.5751 16.6314C16.625 16.5252 16.7127 16.4414 16.8213 16.3963L20.7094 14.7824C21.1122 14.6153 21.0913 14.0396 20.6776 13.9017L11.4287 10.8211C11.0628 10.6992 10.7128 11.043 10.8295 11.4097Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tef3mjick {
  d: path("M10 20L3 20L3 3L20 3L20 10M10.5489 10.528L14.1426 21L16.6527 16.4663L21 14.3L10.5489 10.528Z");
}

</style>
