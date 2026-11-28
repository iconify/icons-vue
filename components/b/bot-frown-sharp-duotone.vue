<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g73d-z9cp"/><path class="r9ze1bg3j"/><path clip-rule="evenodd" class="cifudlb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-frown-sharp-duotone" /></template>
<style>
.cifudlb8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.5C13.5 4.328 12.828 5 12 5C11.172 5 10.5 4.328 10.5 3.5C10.5 2.672 11.172 2 12 2C12.828 2 13.5 2.672 13.5 3.5ZM10 12C10 12.552 9.552 13 9 13C8.448 13 8 12.552 8 12C8 11.448 8.448 11 9 11C9.552 11 10 11.448 10 12ZM16 12C16 12.552 15.552 13 15 13C14.448 13 14 12.552 14 12C14 11.448 14.448 11 15 11C15.552 11 16 11.448 16 12Z");
  stroke: none;
}

.g73d-z9cp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 7H20C20.552 7 21 7.448 21 8V21C21 21.552 20.552 22 20 22H4C3.448 22 3 21.552 3 21V8C3 7.448 3.448 7 4 7H12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r9ze1bg3j {
  d: path("M12 8V3.5M1 14.5H4M23 14.5H20M8.707 17.293L9 17C10 16 11 15.5 12 15.5C13 15.5 14 16 15 17L15.293 17.293");
}

</style>
