<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bs-81nb-f"/><path class="lg2b57bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hut" /></template>
<style>
.bs-81nb-f {
  d: path("m3.27 13.21l8.21-8.67q.52-.54 1.04 0l8.21 8.67q.52.54-.23.54h-17q-.75 0-.23-.54M12 7.5l-2 6.25m2-6.25l2 6.25m-8.97 7l.44-6.5q.03-.5.53-.5h12q.5 0 .53.5l.44 6.5q.03.5-.47.5h-13q-.5 0-.47-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg2b57bfo {
  d: path("M10.25 21.25V18.5a1.75 1.75 0 0 1 3.5 0v2.75");
}

</style>
