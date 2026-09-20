<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="luz6g09wg"/><path class="xd5qf0bqw"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:androidterm" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.luz6g09wg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.986 8.986l8.22 4.747l-8.22 4.748m17.559-.002h-9.34m-5.789 3.473c.627.005 1.26.25 1.765.736l2.088 2.08A15 15 0 0 1 24 21.954a15 15 0 0 1 8.73 2.822l2.097-2.088c1.003-.972 2.528-.979 3.476-.03l.004.013c.95.948.935 2.497-.029 3.461l-2.103 2.073a15 15 0 0 1 2.839 8.763v2.046H8.986v-2.046a15 15 0 0 1 2.846-8.765l-2.1-2.071c-.965-.964-.982-2.513-.031-3.461l-.004-.013a2.4 2.4 0 0 1 1.719-.706");
}

.xd5qf0bqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.679 31.165a2.766 2.766 0 1 0 0 5.53a2.766 2.766 0 0 0 0-5.53m12.642 0a2.766 2.766 0 1 0 2.767 2.766a2.766 2.766 0 0 0-2.766-2.766");
}

</style>
