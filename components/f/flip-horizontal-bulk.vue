<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x1bzzqpec"/><path class="uu8iy5mdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uu8iy5mdc {
  d: path("M13 7a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.x1bzzqpec {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16V8a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l3 3a2.414 2.414 0 0 1 0 3.414l-3 3a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 2 16m20-8v8c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424l-3-3a2.414 2.414 0 0 1 0-3.414l3-3c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582");
}

</style>
