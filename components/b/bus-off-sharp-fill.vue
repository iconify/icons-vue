<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gi_qgwbpn"/><path class="b9kvdvb0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-off-sharp-fill" /></template>
<style>
.b9kvdvb0g {
  d: path("M9 18L15 18M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM18.8233 18.8233C18.5094 19.5172 17.8111 20 17 20C15.8954 20 15 19.1046 15 18C15 17.1889 15.4828 16.4906 16.1767 16.1767M5 18L2 18L2 4L4 4M9 9L2 9M8.6569 4L17.964 4C20.4802 5.6253 22 8.4163 22 11.4118L22 17.3431M14 4L14 9M17 12L22 12M1.7071 1.7071L22.2929 22.2929");
}

.gi_qgwbpn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.1767 16.1767C15.4603 16.5004 14.9999 17.2138 15 18L9 18C9 16.8954 8.1046 16 7 16C5.8954 16 5 16.8954 5 18L2 18L2 9L9 9L16.1767 16.1767ZM12.6569 9L14 9L17 12L22 12L22 18L21.6569 18L12.6569 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
