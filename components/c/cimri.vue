<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="dfj-t_bmq"/><circle class="ymq5icc9l"/><path class="ono1omhgm"/><circle class="jv9uv1crm"/><path class="i21_ggbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cimri" /></template>
<style>
.dfj-t_bmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.005 23.94a2.27 2.27 0 0 1 2.263-2.262h0a2.27 2.27 0 0 1 2.262 2.263v3.733m-4.525-5.996v6.109m4.525-3.847a2.27 2.27 0 0 1 2.263-2.262h0a2.27 2.27 0 0 1 2.262 2.263v3.733m2.464-3.734a2.27 2.27 0 0 1 2.262-2.262m-2.262 0v6.109");
}

.i21_ggbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.229 21.678v6.109");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jv9uv1crm {
  cx: 36.229px;
  cy: 18.963px;
  r: 0.75px;
  fill: currentColor;
}

.ono1omhgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.455 21.678v6.109m-2.248-1.131c-.34.679-1.132 1.131-1.923 1.131h0a2.27 2.27 0 0 1-2.263-2.262v-1.471a2.27 2.27 0 0 1 2.263-2.263h0c.791 0 1.583.453 1.923 1.131");
}

.ymq5icc9l {
  cx: 17.455px;
  cy: 18.963px;
  r: 0.75px;
  fill: currentColor;
}

</style>
