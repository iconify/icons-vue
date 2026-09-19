<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jx82nbs1m"/><path class="sj1-o5bgu"/><path class="nj6u9bcid"/><path class="l09hhdb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foodvisor" /></template>
<style>
.jx82nbs1m {
  cx: 24px;
  cy: 24.78px;
  r: 5.436px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l09hhdb0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.33 35.629v6.356a1.515 1.515 0 0 1-3.03 0v-5.623");
}

.nj6u9bcid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c3.17 0 5.436 3.624 7.121 7.723c1.955 4.752 4.129 8.792 4.129 12.831c0 6.951-5.161 11.377-11.25 11.377s-11.25-4.426-11.25-11.376c0-4.04 2.174-8.08 4.129-12.832C18.564 8.123 20.829 4.5 24 4.5");
}

.sj1-o5bgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.67 35.629v6.356a1.515 1.515 0 0 0 3.03 0v-5.623");
}

</style>
