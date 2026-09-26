<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pq9gj011x"/><path class="ow0zocnmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-heart-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow0zocnmg {
  d: path("M8.9168 13.0295C6.7265 11.1171 5 9.12 5 6.6C5 4.0594 7.149 2 9.8 2C11 2 12.0741 2.4367 13 3.2C13.9259 2.4367 15 2 16.2 2C18.851 2 21 4.0594 21 6.6C21 8.94 19.5113 10.8292 17.5449 12.6183M3 13L3 23M11 15.5L11 13L6.3 13L3 16.3M3 21L5 19L12 19L17 14C17.7811 13.2189 17.7811 11.9511 17 11.17C16.2189 10.3889 14.9511 10.3889 14.17 11.17L11.0498 14.2902");
}

.pq9gj011x {
  fill: currentColor;
  d: path("M3 16.3L6.0071 13.2929C6.1946 13.1054 6.449 13 6.7142 13L9.5 13C10.3284 13 11 13.6716 11 14.5L11.17 14.17L14.17 11.17C14.9511 10.3889 16.2189 10.3889 17 11.17C17.7811 11.9511 17.7811 13.2189 17 14L12.2929 18.7071C12.1054 18.8946 11.851 19 11.5858 19L5 19L3 21L3 16.3Z");
  stroke: none;
}

</style>
