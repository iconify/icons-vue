<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l-1ucdbni"/><path class="suex8lbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-seven-eighth-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l-1ucdbni {
  d: path("M12 2C17.5228 2 22 6.4771 22 12C22 17.5228 17.5228 22 12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2Z");
}

.suex8lbei {
  stroke-linejoin: miter;
  d: path("M7.7574 7.7574L12 12L12 6C15.3137 6 18 8.6863 18 12C18 15.3137 15.3137 18 12 18C8.6863 18 6 15.3137 6 12C6 10.4087 6.6321 8.8826 7.7574 7.7574Z");
}

</style>
