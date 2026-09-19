<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpv8yybei"/><path class="ry_dpbcnu"/><path class="qvkyqfmma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:battlenet" /></template>
<style>
.qvkyqfmma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.414 12.233c-2.245-4.044-7.093-7.432-9.93-6.257s-6.008 6.214-.407 22.009A28.4 28.4 0 0 0 31.102 44.26");
}

.ry_dpbcnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.08 32.942c4.625.078 9.983-2.427 10.384-5.472s-2.377-8.31-18.856-11.357A28.4 28.4 0 0 0 3.5 20.122");
}

.xpv8yybei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.312 27.495c-2.38 3.966-2.89 9.858-.453 11.728s8.386 2.096 19.264-10.652a28.4 28.4 0 0 0 7.083-20.284");
}

</style>
