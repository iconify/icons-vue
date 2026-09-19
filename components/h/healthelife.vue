<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-20 20.523 23.56)" class="jlt5gp4eb"/><ellipse transform="rotate(-65 14.751 28.839)" class="h8ie7nbsl"/><ellipse transform="rotate(-70 27.495 23.562)" class="dcr7p_bbv"/><ellipse transform="rotate(-25 33.242 28.831)" class="wi7-90fvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:healthelife" /></template>
<style>
.dcr7p_bbv {
  cx: 27.49px;
  cy: 23.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.21px;
  ry: 4.22px;
}

.h8ie7nbsl {
  cx: 14.75px;
  cy: 28.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.22px;
  ry: 10.21px;
}

.jlt5gp4eb {
  cx: 20.51px;
  cy: 23.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.22px;
  ry: 10.21px;
}

.wi7-90fvj {
  cx: 33.25px;
  cy: 28.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.21px;
  ry: 4.22px;
}

</style>
