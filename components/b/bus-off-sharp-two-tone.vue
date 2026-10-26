<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wp08n9lro"/><path class="vppnf00bo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vppnf00bo {
  d: path("M9 18L15 18M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM18.8233 18.8233C18.5094 19.5172 17.8111 20 17 20C15.8954 20 15 19.1046 15 18C15 17.1889 15.4828 16.4906 16.1767 16.1767M5 18L2 18L2 4L4 4M9 9L2 9M1.7071 1.7071L22.2929 22.2929");
}

.wp08n9lro {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M18.5066 3.16C21.308 4.9695 23 8.0768 23 11.4118L23 18C23.0001 18.3514 22.8158 18.677 22.5145 18.8577L6.6569 3L17.964 3C18.1565 3 18.3449 3.0556 18.5066 3.16ZM18.9999 18.9999L5 19L2 19C1.4477 19 1 18.5523 1 18L1 4C0.9999 3.4477 1.4477 2.9999 2 2.9999L2.9999 2.9999L18.9999 18.9999Z");
  stroke: none;
}

</style>
