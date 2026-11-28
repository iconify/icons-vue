<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k74b9vqtd"/><path clip-rule="evenodd" class="cifudlb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-frown-sharp" /></template>
<style>
.cifudlb8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.5C13.5 4.328 12.828 5 12 5C11.172 5 10.5 4.328 10.5 3.5C10.5 2.672 11.172 2 12 2C12.828 2 13.5 2.672 13.5 3.5ZM10 12C10 12.552 9.552 13 9 13C8.448 13 8 12.552 8 12C8 11.448 8.448 11 9 11C9.552 11 10 11.448 10 12ZM16 12C16 12.552 15.552 13 15 13C14.448 13 14 12.552 14 12C14 11.448 14.448 11 15 11C15.552 11 16 11.448 16 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k74b9vqtd {
  d: path("M12 8V3.5M1 14.5H4M23 14.5H20M8.707 17.293L9 17C10 16 11 15.5 12 15.5C13 15.5 14 16 15 17L15.293 17.293M4 8H20V21H4V8Z");
}

</style>
