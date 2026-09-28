<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tv-ylcblu"/><path class="w7vrsgblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:anchor-2-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv-ylcblu {
  fill: currentColor;
  d: path("M16 5C16 7.2091 14.2091 9 12 9C9.7909 9 8 7.2091 8 5C8 2.7909 9.7909 1 12 1C14.2091 1 16 2.7909 16 5Z");
  stroke: none;
}

.w7vrsgblj {
  d: path("M12 8L12 17.5M12 17.5C12 19.9853 9.9853 22 7.5 22C5.0147 22 3 19.9853 3 17.5L3 12L5.2929 14.2929M12 17.5C12 19.9853 14.0147 22 16.5 22C18.9853 22 21 19.9853 21 17.5L21 12L18.7071 14.2929");
}

</style>
