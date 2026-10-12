<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uom7lqbtv"/><rect class="np9daacns"/><path class="k_i2081zh"/><path class="n_5-0jyth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badshahi-gate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_i2081zh {
  d: path("M6.5 21.25v-9h11v9");
}

.n_5-0jyth {
  d: path("M9.75 21.25V17c0-1.5 1-2.6 2.25-3.5c1.25.9 2.25 2 2.25 3.5v4.25");
}

.np9daacns {
  width: 17.5px;
  height: 12px;
  x: 3.25px;
  y: 9.25px;
  rx: 1px;
}

.uom7lqbtv {
  d: path("M4.5 9.25a1.5 2.5 0 0 1 3 0Zm5.5 0a2 3 0 0 1 4 0Zm6.5 0a1.5 2.5 0 0 1 3 0Z");
}

</style>
