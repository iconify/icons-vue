<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w3aaq-w9x"/><path clip-rule="evenodd" class="h4vc_cbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-check-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h4vc_cbwt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 10C3 9.4477 3.4477 9 4 9L20 9C20.5523 9 21 9.4477 21 10L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22ZM9.4142 15L8 16.4142L10.2929 18.7071C10.6834 19.0976 11.3166 19.0976 11.7071 18.7071L16 14.4142L14.5858 13L11 16.5858Z");
  stroke: none;
}

.w3aaq-w9x {
  d: path("M7.5 11L7.5 6.5C7.5 4.0147 9.5147 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 11");
}

</style>
