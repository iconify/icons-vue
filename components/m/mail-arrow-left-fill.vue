<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="thko_o8pn"/><path class="k1o206blt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-arrow-left-fill" /></template>
<style>
.k1o206blt {
  d: path("M12 20H5C3.3432 20 2 18.657 2 17V7M2 7C2 5.343 3.3432 4 5 4H19C20.6569 4 22 5.343 22 7M2 7L11.2929 11C11.7154 11.282 12.2846 11.282 12.7071 11L22 7M22 7V10M22 17H16M19 20L16 17L19 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.thko_o8pn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 7C2 5.343 3.3432 4 5 4H19C20.6569 4 22 5.343 22 7L12.7071 11C12.2846 11.282 11.7154 11.282 11.2929 11L2 7Z");
  stroke: none;
}

</style>
