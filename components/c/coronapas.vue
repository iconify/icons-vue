<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w65hx3b2m"/><path class="j9clfzb2x"/><path class="zf21b7bdk"/><path class="eg94xeb3y"/><path class="a41b23yvh"/><path class="tppzd3bwj"/><path class="crr230vhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coronapas" /></template>
<style>
.a41b23yvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.234 20.346a1.46 1.46 0 0 0-1.459-1.563V17.76m.001-1.426v-1.448m2.189 2.143h-1.439m-.75 4.582v7.248");
}

.crr230vhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.803 6.343a1.88 1.88 0 0 0-1.949-1.838l-24.55 1.912a1.937 1.937 0 0 0-1.688 2.121");
}

.eg94xeb3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.876 28.859s4.44-4.795 3.071-7.53s-5.242-1.309-6.17.282");
}

.j9clfzb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.677 28.859s-4.44-4.795-3.072-7.53s5.242-1.309 6.17.282");
}

.tppzd3bwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.404 6.549H10.612a1.94 1.94 0 0 0-1.985 1.895v33.161a1.94 1.94 0 0 0 1.985 1.895h26.792a1.94 1.94 0 0 0 1.984-1.895V8.444a1.94 1.94 0 0 0-1.984-1.895");
}

.w65hx3b2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.342 30.023H30.21m-12.868 3.091H30.21m-12.521-4.255s-5.507-5.616-.375-6.524");
}

.zf21b7bdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.317 20.346a1.46 1.46 0 0 1 1.459-1.563V17.76m0-1.426v-1.448m-2.188 2.143h1.438m7.184 14.54H17.342m12.521-2.71s5.507-5.616.375-6.524");
}

</style>
