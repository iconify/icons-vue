<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yj7thpb3y"/><path class="cbkhf4brw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-heart-two-tone" /></template>
<style>
.cbkhf4brw {
  d: path("M2 10.8473L10.7072 3.4703C11.4532 2.8383 12.5468 2.8383 13.2928 3.4703L22 10.8473M4 9.1528L4 19C4 20.1046 4.8954 21 6 21L18 21C19.1046 21 20 20.1046 20 19L20 9.1528M12 17C10.175 15.4846 8 14.1806 8 12.2361C8 11.0011 9.0745 10 10.4 10C11 10 11.537 10.2123 12 10.5833C12.463 10.2123 13 10 13.6 10C14.9255 10 16 11.0011 16 12.2361C16 14.1806 13.825 15.4846 12 17Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yj7thpb3y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0604 2.70725C11.1794 1.75935 12.8203 1.75928 13.9393 2.70725L22.6463 10.0842C23.0676 10.4412 23.1194 11.072 22.7625 11.4934C22.4056 11.9147 21.7747 11.9674 21.3533 11.6106L20.9998 11.3108V19.0002C20.9996 20.6569 19.6566 22.0002 17.9998 22.0002H5.99983C4.34311 22.0002 3.00008 20.6569 2.99983 19.0002V11.3108L2.64632 11.6106C2.22495 11.9675 1.59412 11.9147 1.23714 11.4934C0.880186 11.072 0.931985 10.4412 1.35335 10.0842L10.0604 2.70725Z");
  stroke: none;
}

</style>
