<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xfeuobc1g"/><path class="yi9afv_df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-check-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xfeuobc1g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.9998 2.9963C12.552 2.99638 12.9998 3.44406 12.9998 3.9963V8.00021C12.9999 9.657 14.343 11.0002 15.9998 11.0002H19.9998C20.552 11.0002 20.9997 11.448 20.9998 12.0002V20.0002C20.9996 21.6569 19.6566 23.0002 17.9998 23.0002H5.99983C4.34311 23.0002 3.00008 21.6569 2.99983 20.0002V12.3108L2.64632 12.6106C2.22496 12.9675 1.59413 12.9147 1.23714 12.4934C0.880186 12.072 0.931985 11.4412 1.35335 11.0842L10.0604 3.70724C10.6197 3.23339 11.3109 2.9963 11.9998 2.9963Z");
  stroke: none;
}

.yi9afv_df {
  d: path("M2 11.8473L10.7072 4.4703C11.0802 4.1543 11.5401 3.9963 12 3.9963M4 10.1528L4 20C4 21.1046 4.8954 22 6 22L18 22C19.1046 22 20 21.1046 20 20L20 12M9 22L9 19C9 17.3431 10.3431 16 12 16C13.6569 16 15 17.3431 15 19L15 22M16 5.6L18.3333 8L22 2");
}

</style>
