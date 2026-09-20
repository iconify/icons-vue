<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_mr-pb8v"/><path class="kaikf9fob"/><path class="gi7xt2bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dicio" /></template>
<style>
.a_mr-pb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.745 38.148zs.176 4.63 9.315 4.339c9.138-.293 20.683-2.377 25.682-12.874S38.704 5.604 14.509 5.5c0 0-5.356 29.949 1.162 29.924c-6.324-.93-9.74.269-9.926 2.724");
}

.gi7xt2bas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.112 24.22a8.18 8.18 0 0 0 16.049 0");
}

.kaikf9fob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.137 12.07zc2.98.093 4.188 2.322 4.188 5.188v5.423c0 2.865-1.323 5.188-4.188 5.188c-2.866 0-4.19-2.323-4.19-5.188v-5.423c0-2.902 1.157-5.038 4.19-5.188m-.022 18.733v4.138");
}

</style>
