<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k6jy_6bpf"/><path class="v9u-zvj3g"/><path class="nrbmjwbal"/><path class="wx7721bcb"/><circle class="qdotesbju"/><circle class="e_hqr5bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beaky-news" /></template>
<style>
.e_hqr5bdg {
  cx: 26.567px;
  cy: 18.628px;
  r: 0.75px;
  fill: currentColor;
}

.k6jy_6bpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.923 30.263V5.5h20.814a9.067 9.067 0 0 1 9.067 9.067a9.06 9.06 0 0 1-4.898 8.046c3.195 1.84 5.35 5.28 5.35 9.232c0 5.884-4.77 10.655-10.654 10.655h-8.486");
}

.nrbmjwbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.928 42.5c5.419 0 7.675-1.652 7.675-7.675a7.675 7.675 0 0 0-7.675-7.676H11.923");
}

.qdotesbju {
  cx: 26.567px;
  cy: 18.628px;
  r: 2.065px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v9u-zvj3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.53 27.15v-8.444a5.036 5.036 0 0 1 10.073 0v16.119");
}

.wx7721bcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.743 30.263c0 6.758 5.479 12.237 12.237 12.237h5.135a6.12 6.12 0 0 0 6.09-6.72c-.303-3.18-3.157-5.517-6.352-5.517zm.284 2.632h7.896M7.515 36.6h4.279m19.809-15.785l3.238-1.951l-3.665-2.19");
}

</style>
