<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y94o0y-rw"/><path clip-rule="evenodd" class="wlo1dvg-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alien-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wlo1dvg-n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.7565 13.3761C10.2136 14.2887 8.7544 14.1885 7.4972 13.1522C6.2401 12.1161 5.6609 10.5364 6.2038 9.6239C6.7467 8.7114 8.2058 8.8116 9.463 9.8478C10.7201 10.8839 11.2993 12.4636 10.7565 13.3761ZM17.7963 9.6239C18.3391 10.5364 17.7599 12.1161 16.5028 13.1522C15.2456 14.1885 13.7864 14.2887 13.2435 13.3761C12.7007 12.4636 13.2799 10.8839 14.537 9.8478C15.7942 8.8116 17.2534 8.7114 17.7963 9.6239Z");
  stroke: none;
}

.y94o0y-rw {
  d: path("M3 10C3 5.5817 7.0295 2 12 2C16.9705 2 21 5.5817 21 10C21 15.5 15.6 22 12 22C8.4 22 3 15.5 3 10Z");
}

</style>
