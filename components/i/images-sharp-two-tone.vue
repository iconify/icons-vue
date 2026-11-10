<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pui23lbnu"/><path class="oy3ht5cdt"/><path clip-rule="evenodd" class="s84gf295k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy3ht5cdt {
  d: path("M3 7V21H17M21 14.14L17.889 11.27L14.778 13.42L11.667 10.56L7 14.85M7 3H21V17H7V3Z");
}

.pui23lbnu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 20H17V22H3C2.448 22 2 21.55 2 21V7H4V20ZM21 2C21.552 2 22 2.45 22 3V17C22 17.55 21.552 18 21 18H7C6.448 18 6 17.55 6 17V3C6 2.45 6.448 2 7 2H21Z");
  stroke: none;
}

.s84gf295k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 7C12 7.55 11.552 8 11 8C10.448 8 10 7.55 10 7C10 6.45 10.448 6 11 6C11.552 6 12 6.45 12 7Z");
  stroke: none;
}

</style>
