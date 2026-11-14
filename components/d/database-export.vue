<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t45t2abea"/><path class="gnjqagbmh"/><path class="r4vlhk6on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-export" /></template>
<style>
.gnjqagbmh {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c.858 0 1.686-.048 2.463-.135m5.235-1.872c.197-.237.302-.487.302-.743");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4vlhk6on {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.t45t2abea {
  d: path("M15.17 21.022c-.973.146-2.045.228-3.17.228c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.555");
}

</style>
