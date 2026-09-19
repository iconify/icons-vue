<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shazf9dab"/><rect class="t_brh_rhl"/><path class="qwj0rj64y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:douban" /></template>
<style>
.qwj0rj64y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.37 30.03l-3.98 12.83m-13.4-7.97l2.47 7.97");
}

.shazf9dab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.45 42.86h37m-37-35.8h37");
}

.t_brh_rhl {
  width: 31.53px;
  height: 17.1px;
  x: 8.18px;
  y: 12.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.06px;
}

</style>
