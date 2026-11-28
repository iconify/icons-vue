<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="acr8g3bku"/><path clip-rule="evenodd" class="cvh6_xsyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-off-sharp" /></template>
<style>
.acr8g3bku {
  d: path("M3.716 3.716C2.679 4.439 2 5.64 2 7C2 9.209 3.791 11 6 11V19C6 20.105 6.895 21 8 21C9.105 21 10 20.105 10 19V10M14 14V19C14 20.105 14.895 21 16 21C17.105 21 18 20.105 18 19V18M6 17H10M14 17H17M18 13.343V11C20.209 11 22 9.209 22 7C22 4.791 20.209 3 18 3C15.791 3 14 4.791 14 7V9.343M1.707 1.707L22.293 22.293");
}

.cvh6_xsyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 7C19 7.552 18.552 8 18 8C17.448 8 17 7.552 17 7C17 6.448 17.448 6 18 6C18.552 6 19 6.448 19 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
