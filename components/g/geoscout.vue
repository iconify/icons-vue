<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1uontkvh"/><path class="qd8fnjbxc"/><path class="y7c0-ml5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geoscout" /></template>
<style>
.n1uontkvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.196 22.121C5.198 13.783 11.404 2.5 24 2.5s18.802 11.283 17.804 19.621C40.748 30.947 31.014 39.021 24 45.5C16.985 39.02 7.252 30.947 6.196 22.121");
}

.qd8fnjbxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.812 39.785l7.705-7.705l-6.538-6.538l8.14-8.14l11.98 11.982");
}

.y7c0-ml5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.295 20.574l1.795-1.795c.644-.644.644-2.09 0-2.734l-2.556-2.556c-.701-.701-2.274-.701-2.975 0l-7.507 7.058c-1.148 1.08-1.316 3.753-.073 4.995");
}

</style>
