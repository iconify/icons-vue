<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="eo60n2g2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-off-outline-thin" /></template>
<style>
.eo60n2g2k {
  d: path("m6.5 6.5 10 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

</style>
