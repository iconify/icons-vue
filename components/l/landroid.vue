<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bnzvoybip"/><circle class="q2z6hpq5y"/><circle class="v683t1bkq"/><path class="knwbwjjro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:landroid" /></template>
<style>
.bnzvoybip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.2 18.4h21.5v17.1l-1.8 1.8H15l-1.8-1.8Zm0-2c0-12.8 21.5-12.7 21.5 0Zm20.1 0v2m-18.2 0v-2");
}

.knwbwjjro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 43.5h-5.6v-6.2m-10.9 0v6.2H13M29 7.8l1.5-3.3m-13.1 0l1.5 3.3m-3.6 12.7v10.3h3.4v1.8h1.7V35h7.2v-2.4h1.7v-1.8h3.4V20.4Zm2.3 2.2v2m1.9-2v2m1.8-2v2m1.8-2v2m1.8-2v2m1.8-2v2m1.9-2v2m1.8-2v2m-20 6.1za.79.79 0 0 1-.8-.8V20a.79.79 0 0 1 .8-.8a.79.79 0 0 1 .8.8v10c.1.4-.3.8-.8.8m27.2 0za.79.79 0 0 1-.8-.8V20a.79.79 0 0 1 .8-.8a.79.79 0 0 1 .8.8v10a.86.86 0 0 1-.8.8M18.5 43.5h10.9");
}

.q2z6hpq5y {
  cx: 19px;
  cy: 12.4px;
  r: 0.8px;
  fill: currentColor;
}

.v683t1bkq {
  cx: 29px;
  cy: 12.4px;
  r: 0.8px;
  fill: currentColor;
}

</style>
