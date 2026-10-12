<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t_4-59y1e"/><path class="df1wt6xxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dungeon-door-sharp" /></template>
<style>
.df1wt6xxy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 17.75h.01");
}

.t_4-59y1e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 21.25V11a7.25 7.25 0 0 1 14.5 0v10.25ZM10.5 7v4.5m3-4.5v4.5m-8.75 2.75h14.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
