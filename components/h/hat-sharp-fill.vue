<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oml68njng"/><path class="lq6kgkb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hat-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lq6kgkb0b {
  d: path("M2 13L2 14C2 16.7614 4.2386 19 7 19L17 19C19.7614 19 22 16.7614 22 14L22 13");
}

.oml68njng {
  fill: currentColor;
  d: path("M12 14L17.4285 14L17.5793 14L17.9154 14C18.4041 14 18.8212 14.3532 18.9017 14.8353L19.4863 18.3353L19.5288 18.5895C19.5379 18.644 19.5425 18.6991 19.5425 18.7544C19.5425 19.3067 19.0948 19.7544 18.5425 19.7544L12 19.7544L5.4575 19.7543C4.9053 19.7543 4.4575 19.3066 4.4575 18.7543C4.4575 18.6991 4.4621 18.644 4.4712 18.5895L4.5137 18.3352L5.0982 14.8353C5.1787 14.3532 5.5958 14 6.0845 14L6.4206 14L6.5715 14ZM17.7326 7.8353L18.2337 10.8353C18.2428 10.8897 18.2473 10.9448 18.2473 11C18.2473 11.5523 17.7996 12 17.2473 12L12 12L6.7526 12C6.2003 12 5.7526 11.5523 5.7526 11C5.7526 10.9448 5.7572 10.8897 5.7663 10.8353L6.7684 4.8353C6.8489 4.3532 7.266 4 7.7547 4L9.857 4C10.0622 4 10.2624 4.0631 10.4305 4.1807L12 5.2794L13.5694 4.1808C13.7375 4.0631 13.9377 4 14.1429 4L16.2453 4C16.734 4 17.1511 4.3532 17.2316 4.8353Z");
  stroke: none;
}

</style>
