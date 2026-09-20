<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rma_jepfg"/><path class="eps7n7thh"/><path class="pbb85xd_m"/><path class="jszq3vk8j"/><path class="e4eowacni"/><path class="zqt06zbwt"/><path class="bapcedvpx"/><path class="um5ds7hqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:frag" /></template>
<style>
.bapcedvpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.663 14.11c1.748.006 3.486.034 5.183.085m7.697-1.131c.644.067 1.267.062 1.86.139l-.008 3.84l-1.211.874a43 43 0 0 0-3.894-.901l-.996-1.455V9.142l1.141-.82h3.804l1.156 1.293v.533M33.93 29.674c0 5.484-4.446 9.93-9.93 9.93s-9.93-4.446-9.93-9.93s4.446-9.929 9.93-9.929s9.93 4.446 9.93 9.93z");
}

.e4eowacni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.375 18.376V8.32h4.579m2.04 4.291c1.627-.102 3.322-.176 5.057-.22");
}

.eps7n7thh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.547 29.674c0 6.93-5.617 12.547-12.547 12.547s-12.547-5.617-12.547-12.547S17.071 17.128 24 17.128s12.546 5.617 12.547 12.546");
}

.jszq3vk8j {
  fill: currentColor;
  d: path("M27.669 24.288a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0m-7.473 6.365a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0m1.918 2.746a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.pbb85xd_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.224 29.674a1.224 1.224 0 1 1-2.448 0a1.224 1.224 0 0 1 2.448 0");
}

.rma_jepfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.197 26.743l4.932-1.96c.764-.304 1.371-1.227 1.371-2.049V7.74a1.957 1.957 0 0 0-1.953-1.961H7.46A1.957 1.957 0 0 0 5.5 7.733v15.001c0 .822.607 1.745 1.37 2.048l4.958 1.97");
}

.um5ds7hqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.53 29.674a5.53 5.53 0 0 1-11.06 0a5.53 5.53 0 0 1 11.06.001z");
}

.zqt06zbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.375 13.231a91 91 0 0 1 4.577-.475m-4.596.478l.019-.003m6.628 3.574V8.321h4.716l1.519 1.083v2.09l-1.3.985l1.3.985v2.714m9.216.275l-2.19-8.132h-1.992l-2.164 7.784");
}

</style>
