<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kjxfnp83k"/><path class="hepgt_eac"/><path class="mtmapjx1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-coins-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hepgt_eac {
  fill: currentColor;
  d: path("M13.4629 10.4631C14.6345 9.2914 16.5354 9.2914 17.707 10.4631C18.8785 11.6347 18.8786 13.5356 17.707 14.7072L13 19.4142C12.625 19.7891 12.1163 20.0001 11.5859 20.0002L5.4141 20.0002L3.707 21.7072C3.4211 21.993 2.9908 22.0787 2.6172 21.924C2.2437 21.7693 2.0002 21.4045 2 21.0002L2 16.3C2 16.0348 2.1055 15.7805 2.293 15.593L5.2998 12.5861C5.6747 12.2112 6.1835 12.0003 6.7139 12.0002L9.5 12.0002C10.1713 12.0002 10.7794 12.2659 11.2285 12.6965L13.4629 10.4631Z");
  stroke: none;
}

.kjxfnp83k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M22 4.5C22 6.433 20.433 8 18.5 8C16.567 8 15 6.433 15 4.5C15 2.567 16.567 1 18.5 1C20.433 1 22 2.567 22 4.5ZM13 5.5C13 7.433 11.433 9 9.5 9C7.567 9 6 7.433 6 5.5C6 3.567 7.567 2 9.5 2C11.433 2 13 3.567 13 5.5Z");
  stroke: none;
}

.mtmapjx1s {
  d: path("M3 13L3 23");
}

</style>
