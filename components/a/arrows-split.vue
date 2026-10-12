<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wosubxdan"/><path class="fca-dbchs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrows-split" /></template>
<style>
.fca-dbchs {
  d: path("M5.75 9.75v-4h4m4.5 0h4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wosubxdan {
  d: path("M12 20.25V12L5.75 5.75M12 12l6.25-6.25");
}

</style>
