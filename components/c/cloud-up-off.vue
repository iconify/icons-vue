<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jhwoxibja"/><path class="fsi9qeb8f"/><path class="e5_znabmz"/><path class="mf0oe2hhn"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cloud-up-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e5_znabmz {
  d: path("M8.625 11.28a1 1 0 1 1-1.25-1.56l2.5-2a1 1 0 1 1 1.25 1.56z");
}

.fsi9qeb8f {
  d: path("M11.5 16a1 1 0 1 1-2 0V8.5a1 1 0 0 1 2 0z");
}

.jhwoxibja {
  fill-rule: evenodd;
  d: path("M11 3h-1a4 4 0 0 0-3.874 3H6a4 4 0 1 0 0 8h8a4 4 0 0 0 .899-7.899A4 4 0 0 0 11 3M7.676 8l.387-1.501A2 2 0 0 1 10 5h1c.937 0 1.743.65 1.95 1.549l.28 1.221l1.221.28A2.002 2.002 0 0 1 14 12H6a2 2 0 1 1 0-4z");
}

.mf0oe2hhn {
  d: path("M13.625 9.72a1 1 0 1 1-1.25 1.56l-2.5-2a1 1 0 0 1 1.25-1.56z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
