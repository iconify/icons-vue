<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="by6k8zbjb"/><path clip-rule="evenodd" class="zddkvybeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:houses-sharp-duotone" /></template>
<style>
.by6k8zbjb {
  stroke-opacity: 0.4;
  d: path("M1.6141 7.1912L2 6.8909L7 3L10.456 5.6894L10.8419 5.9897M4 5.3346L4 10.7134L4 11.7134");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zddkvybeb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.3857 7.2108C13.5613 7.0742 13.7775 7 14 7C14.2224 7 14.4386 7.0742 14.6142 7.2108L23 13.7362L21.7714 15.3153L21 14.7147L21 20.9999C20.9998 21.5521 20.5522 21.9997 20 21.9999L8 21.9999C7.4478 21.9997 7.0002 21.5521 7 20.9999L7 14.7147L6.2285 15.3153L5 13.7362L13.3857 7.2108ZM12 20L16 20L16 18C16 16.8954 15.1046 16 14 16C12.8954 16 12 16.8954 12 18L12 20Z");
  stroke: none;
}

</style>
