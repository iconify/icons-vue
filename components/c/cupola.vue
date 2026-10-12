<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kzdkjrblp"/><rect class="iwc8hcg1p"/><path class="c8nhdccre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cupola" /></template>
<style>
.c8nhdccre {
  d: path("M10.5 15.25V14a1.5 1.5 0 0 1 3 0v1.25ZM6.67 9.08l2.41-2.41q.42-.42 1.02-.42h3.8q.6 0 1.02.42l2.41 2.41q.42.42-.18.42H6.85q-.6 0-.18-.42M12 6.25v-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwc8hcg1p {
  width: 8px;
  height: 8.75px;
  x: 8px;
  y: 9.5px;
  rx: 0.5px;
}

.kzdkjrblp {
  width: 15.5px;
  height: 3px;
  x: 4.25px;
  y: 18.25px;
  rx: 0.75px;
}

</style>
