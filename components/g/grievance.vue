<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="meya5wbqf"/><path class="j-tkk1buy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grievance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-tkk1buy {
  d: path("m5.5 17l-2 4.5L9 18.75M12 7.5v3.75m0 3h.01");
}

.meya5wbqf {
  d: path("m13.087 2.892l.594.625a1.5 1.5 0 0 0 1.358.441l.847-.156a1.5 1.5 0 0 1 1.759 1.277l.113.855a1.5 1.5 0 0 0 .84 1.155l.777.372a1.5 1.5 0 0 1 .672 2.067l-.41.758a1.5 1.5 0 0 0 0 1.428l.41.758a1.5 1.5 0 0 1-.672 2.067l-.777.372a1.5 1.5 0 0 0-.84 1.155l-.113.855a1.5 1.5 0 0 1-1.759 1.277l-.847-.156a1.5 1.5 0 0 0-1.358.441l-.594.625a1.5 1.5 0 0 1-2.174 0l-.594-.625a1.5 1.5 0 0 0-1.358-.441l-.847.156a1.5 1.5 0 0 1-1.759-1.277l-.113-.855a1.5 1.5 0 0 0-.84-1.155l-.777-.372a1.5 1.5 0 0 1-.672-2.067l.41-.758a1.5 1.5 0 0 0 0-1.428l-.41-.758a1.5 1.5 0 0 1 .672-2.067l.777-.372a1.5 1.5 0 0 0 .84-1.155l.113-.855a1.5 1.5 0 0 1 1.759-1.277l.847.156a1.5 1.5 0 0 0 1.358-.441l.594-.625a1.5 1.5 0 0 1 2.174 0");
}

</style>
