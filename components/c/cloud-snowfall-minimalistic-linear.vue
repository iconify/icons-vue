<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y_9s_-bnx"/><path class="u1sbtfbps"/><path class="tgagj5b1m"/><path class="w4394pj2y"/><path class="qpf-imbkb"/><path class="v6662i_bw"/><path class="e4kpjpbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-snowfall-minimalistic-linear" /></template>
<style>
.e4kpjpbrv {
  stroke-linejoin: round;
  d: path("M15 19.5H15.0001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpf-imbkb {
  stroke-linejoin: round;
  d: path("M12 21H12.0001");
}

.tgagj5b1m {
  stroke-linejoin: round;
  d: path("M9 19.5H9.0001");
}

.u1sbtfbps {
  stroke-linejoin: round;
  d: path("M9 16.5H9.0001");
}

.v6662i_bw {
  stroke-linejoin: round;
  d: path("M15 16.5H15.0001");
}

.w4394pj2y {
  stroke-linejoin: round;
  d: path("M12 18H12.0001");
}

.y_9s_-bnx {
  d: path("M6.28571 19C3.91878 19 2 17.1038 2 14.7647C2 12.4256 3.91878 10.5294 6.28571 10.5294C6.56983 10.5294 6.8475 10.5567 7.11616 10.6089M17.5 18.8722C20.0726 18.3221 22 16.0599 22 13.3529C22 10.8811 20.393 8.78024 18.1551 8.01498C17.5693 7.81468 16.9404 7.70588 16.2857 7.70588C15.6178 7.70588 14.9767 7.81911 14.381 8.02721M7.11616 10.6089C6.88706 9.9978 6.7619 9.33687 6.7619 8.64706C6.7619 5.52827 9.32028 3 12.4762 3C15.4159 3 17.8371 5.19371 18.1551 8.01498M7.11616 10.6089C7.68058 10.7184 8.20528 10.9374 8.66667 11.2426");
}

</style>
