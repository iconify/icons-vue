<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lqp-7-kpp"/><path class="dn7mckbya"/><circle class="x02lk-0hf"/><path class="yj425eb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:egg-beater" /></template>
<style>
.dn7mckbya {
  d: path("M12 5.25v6.5m-3 0h6m-3-4h3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqp-7-kpp {
  width: 7.5px;
  height: 2.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

.x02lk-0hf {
  cx: 17.25px;
  cy: 7.75px;
  r: 2.25px;
}

.yj425eb9d {
  d: path("M9 11.75C6.5 13 6.5 20 9 21.25c2.5-1.25 2.5-8.25 0-9.5m6 0c-2.5 1.25-2.5 8.25 0 9.5c2.5-1.25 2.5-8.25 0-9.5");
}

</style>
