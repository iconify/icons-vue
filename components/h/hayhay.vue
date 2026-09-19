<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvh581k_h"/><path class="lz_duyb_k"/><path class="j_6ta9lwm"/><circle class="cpk0fnbgt"/><path class="bn-bzibws"/><circle class="gy5hm0bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hayhay" /></template>
<style>
.bn-bzibws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.189 20.358h-4.766c-2 0-3.622 1.63-3.622 3.642s1.621 3.642 3.622 3.642h4.766");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gy5hm0bwj {
  cx: 40.422px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.j_6ta9lwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.477 15.965v3.357c0 1.12-.916 2.035-2.035 2.035s-2.035-.916-2.035-2.035v-3.357m-2.06 3.4c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4");
}

.lz_duyb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.159 28.037v3.3c0 1.1-.9 2-2 2s-2-.9-2-2v-3.3m-2.112 3.4c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4m-10.11-2.7v8.1m0-3.4c0-1.1.9-2 2-2s2 .9 2 2v3.3M14.02 13.365v8m5.3-8v8m-5.3-4.1h5.3m12.157 2.159v2.747a2.04 2.04 0 0 1-2.035 2.035c-.61 0-1.12-.204-1.424-.61");
}

.mvh581k_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.159 31.437v2.7c0 1.1-.9 2-2 2c-.6 0-1.1-.2-1.4-.6");
}

</style>
