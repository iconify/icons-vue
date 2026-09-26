<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qi287dm-m"/><path class="wkvc86bnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-arrow-left-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qi287dm-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 2L3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22L21 22C21.5523 22 22 21.5523 22 21L22 13C22 12.4477 21.5523 12 21 12L12 12L12 3C12 2.4477 11.5523 2 11 2ZM4 17L8.2929 12.7071C8.6834 12.3166 9.3166 12.3166 9.7071 12.7071L13 16L16.3062 13.5204C16.7043 13.2218 17.2614 13.2614 17.6133 13.6133L20 16L20 19C20 19.5523 19.5523 20 19 20L5 20C4.4477 20 4 19.5523 4 19L4 17ZM9.5 7.5C9.5 6.6716 8.8284 6 8 6C7.1716 6 6.5 6.6716 6.5 7.5C6.5 8.3284 7.1716 9 8 9C8.8284 9 9.5 8.3284 9.5 7.5Z");
  stroke: none;
}

.wkvc86bnt {
  d: path("M22 6L15 6M18.2929 2.7071L15 6L18.2929 9.2929");
}

</style>
