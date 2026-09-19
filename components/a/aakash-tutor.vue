<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="g1dzlby7n"/><path class="fot8_pyty"/><path class="iapfn7v8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aakash-tutor" /></template>
<style>
.fot8_pyty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.963 42.5a3.17 3.17 0 0 0 2.943-2.018c.673-1.598-.084-3.448-1.766-4.12c-7.148-2.86-11.352-8.662-13.118-17.576c-.337-1.682-2.019-2.859-3.7-2.522s-2.86 2.018-2.523 3.7c2.102 11.016 7.82 18.5 16.902 22.284q.63.252 1.262.252");
}

.g1dzlby7n {
  cx: 23.994px;
  cy: 8.695px;
  r: 3.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iapfn7v8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.755 19.668c-1.79 8.459-5.983 13.941-12.906 16.693c-1.598.673-2.439 2.523-1.766 4.12a3.17 3.17 0 0 0 2.943 2.02c.42 0 .841-.085 1.178-.253c6.222-2.523 10.763-6.727 13.79-12.698");
}

</style>
