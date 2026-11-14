<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhumiclnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:genre-electronic" /></template>
<style>
.jhumiclnz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.091 4.916q.93-.949 2.057-.246t.684 1.956l-.665 1.873q-.13.366.094.684q.224.317.613.317h1.001q1.383-.001 1.934 1.268t-.393 2.279l-5.374 5.757q-.916.979-2.06.278q-1.143-.701-.687-1.963l.768-2.112q.134-.367-.09-.687T9.358 14H8.25q-1.406-.001-1.952-1.297q-.546-1.295.436-2.302z");
}

</style>
