<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvkpyc0wg"/><path class="t9ia5kx4y"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:floor-lamp-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvkpyc0wg {
  d: path("m5 10 4 -4h6l4 4Z");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.t9ia5kx4y {
  d: path("M12 10v10");
}

</style>
