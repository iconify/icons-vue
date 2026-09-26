<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jb9d8n0ki"/><path class="lcvywl2go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:language-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jb9d8n0ki {
  d: path("M1.9138 11.1939L6 2L10.0862 11.1939M3.3333 8L8.6667 8");
}

.lcvywl2go {
  stroke-opacity: 0.4;
  d: path("M11 15L23 15M14 15C14.4767 16.1439 15.5203 18.0076 17 19.543C18.1074 20.6922 19.459 21.6576 21 22L21.1071 22.0238M20 15C19.5234 16.1439 18.4797 18.0076 17 19.543C15.8926 20.6922 14.541 21.6576 13 22L12.8929 22.0238M15 11L19 11");
}

</style>
