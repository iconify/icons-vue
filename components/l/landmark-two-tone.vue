<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqjfbuzue"/><path class="tzpvy3byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:landmark-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tqjfbuzue {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.8392 6.1534C2.3253 6.4053 1.9996 6.9278 1.9996 7.5001C1.9996 8.3286 2.6714 9.0002 3.4999 9L20.5 9C21.3286 9.0002 22.0004 8.3286 22.0004 7.5001C22.0004 6.9278 21.6747 6.4053 21.1608 6.1534L13.3215 2.3067C12.9102 2.1049 12.4582 1.9999 12 1.9999C11.5418 1.9999 11.0898 2.1049 10.6785 2.3067L2.8392 6.1534Z");
  stroke: none;
}

.tzpvy3byg {
  d: path("M3.2797 7.0511C3.1085 7.1351 2.9999 7.3093 2.9999 7.5C2.9999 7.7761 3.2238 8 3.5 8L20.5 8C20.7762 8 21 7.7761 21 7.5C21 7.3093 20.8915 7.1351 20.7203 7.0511L12.881 3.2045C12.6068 3.0699 12.3054 2.9999 12 2.9999C11.6946 2.9999 11.3932 3.0699 11.119 3.2045L3.2797 7.0511ZM6 12L6 17M12 12L12 17M18 12L18 17M3 21L21 21");
}

</style>
