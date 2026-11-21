<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ye63z1a3n"/><path class="n1ys4e0qo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:beehouse-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n1ys4e0qo {
  d: path("M1.3714 8.2514L2 8L12 4L22 8L22.6286 8.2514M12 4L12 2L12 1M3.8779 7.2673L4 8L6 20L18 20L20 8L20.1221 7.2673M9 10L10 10L14 10L15 10M12 20L12 22L12 23");
}

.ye63z1a3n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.9511 13.7894L2.8886 7.4144C2.8796 7.3601 2.875 7.3051 2.875 7.25C2.875 6.8411 3.124 6.4734 3.5036 6.3215L11.6286 3.0715C11.7467 3.0243 11.8728 3 12 3C12.1272 3 12.2533 3.0243 12.3714 3.0715L20.4964 6.3215C20.876 6.4734 21.125 6.8411 21.125 7.25C21.125 7.3051 21.1204 7.3601 21.1114 7.4144L18.9864 20.1644C18.906 20.6466 18.4888 21 18 21L6 21C5.5112 21 5.094 20.6466 5.0136 20.1644Z");
  stroke: none;
}

</style>
