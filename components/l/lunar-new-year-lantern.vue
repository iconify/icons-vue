<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gb_dqzc6s"/><rect class="c-o8zkk9b"/><path class="rlwk8tbqd"/><path class="ncsf6igep"/><rect class="hd2e_ke5f"/><path class="zcdajob3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-new-year-lantern" /></template>
<style>
.c-o8zkk9b {
  width: 6.5px;
  height: 2.5px;
  x: 8.75px;
  y: 3.5px;
  rx: 0.6px;
}

.gb_dqzc6s {
  d: path("M12 2.75v.75");
}

.hd2e_ke5f {
  width: 6.5px;
  height: 2.5px;
  x: 8.75px;
  y: 17px;
  rx: 0.6px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ncsf6igep {
  d: path("M12 6v11M8.25 6.75c-1.5 3-1.5 6.5 0 9.5m7.5-9.5c1.5 3 1.5 6.5 0 9.5");
}

.rlwk8tbqd {
  d: path("M12 6c4.75 0 8 2.5 8 5.5S16.75 17 12 17s-8-2.5-8-5.5S7.25 6 12 6");
}

.zcdajob3n {
  d: path("M12 19.5v1.75m-1.5-1.75v1.25m3-1.25v1.25");
}

</style>
