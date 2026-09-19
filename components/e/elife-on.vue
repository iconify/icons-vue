<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="oo9xtihkq"/><circle class="kdin81byz"/><path class="u3sy4b_fj"/><rect class="zmbunhmsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elife-on" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kdin81byz {
  cx: 18.647px;
  cy: 21.012px;
  r: 0.75px;
  fill: currentColor;
}

.oo9xtihkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.658 20.8v6.782h3.391m17.958 0V20.8l4.493 6.782V20.8");
}

.u3sy4b_fj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.647 23.089v4.493m-6.978-.856a1.7 1.7 0 0 1-1.474.856h0c-.936 0-1.695-.76-1.695-1.696v-1.102c0-.936.76-1.695 1.696-1.695h0c.936 0 1.695.759 1.695 1.695v.551H8.5m18.306 1.391a1.7 1.7 0 0 1-1.473.856h0c-.937 0-1.696-.76-1.696-1.696v-1.102c0-.936.76-1.695 1.696-1.695h0c.936 0 1.695.759 1.695 1.695v.551h-3.39m-2.386 2.247v-5.595c0-.656.53-1.187 1.186-1.187h0c.585 0 .95.173 1.2.496m-3.392 1.793h2.374");
}

.zmbunhmsp {
  width: 4.493px;
  height: 6.782px;
  x: 28.722px;
  y: 20.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.247px;
  ry: 2.247px;
}

</style>
