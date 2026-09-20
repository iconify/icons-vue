<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn_pu6j-z"/><path class="lcdiu5g_w"/><path class="mihda9d9w"/><path class="u-hmh_b8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eval-dataset-outline-thin" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcdiu5g_w {
  d: path("M9 11v6");
}

.mihda9d9w {
  d: path("M12 9v8");
}

.u-hmh_b8z {
  d: path("M15 12v5");
}

</style>
