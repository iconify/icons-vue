<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="k1vymobgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuprumpdf" /></template>
<style>
.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.k1vymobgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.09 30V18h2.037a6 6 0 0 1 6 6h0a6 6 0 0 1-6 6zm12.393-11.964h5.982m-5.982 5.982h3.9m-3.9-5.982V30m-22.948-.031V18.004h4.018a4.018 4.018 0 0 1 0 8.037H9.535");
}

</style>
