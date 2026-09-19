<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x89qxxbkm"/><path class="j2czw9b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:balance-pay" /></template>
<style>
.j2czw9b3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.224 17.913l6.638 12.29H4.5m39-12.29l-5.45 10.091m-1.188 2.199l-3.319 6.145");
}

.x89qxxbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.145 25.565a4.638 4.638 0 1 1-9.276 0V22.55a4.638 4.638 0 1 1 9.276 0m0 7.653v-12.29M4.5 30.203V11.652h6.073c3.434 0 6.217 2.79 6.217 6.23s-2.783 6.23-6.217 6.23H4.5");
}

</style>
