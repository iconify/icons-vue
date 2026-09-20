<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="i7qvrkbrz"/><path class="k049mh13f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:engine-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i7qvrkbrz {
  d: path("M248 120v48a8 8 0 0 1-8 8h-16l-37.66 37.66a8 8 0 0 1-5.65 2.34h-77.38a8 8 0 0 1-5.65-2.34l-39.32-39.32a8 8 0 0 1-2.34-5.65V80a8 8 0 0 1 8-8h116.69a8 8 0 0 1 5.65 2.34L224 112h16a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k049mh13f {
  d: path("M240 104h-12.69L192 68.69A15.86 15.86 0 0 0 180.69 64H140V40h24a8 8 0 0 0 0-16h-64a8 8 0 0 0 0 16h24v24H64a16 16 0 0 0-16 16v52H24v-24a8 8 0 0 0-16 0v64a8 8 0 0 0 16 0v-24h24v20.69A15.86 15.86 0 0 0 52.69 180L92 219.31a15.86 15.86 0 0 0 11.31 4.69h77.38a15.86 15.86 0 0 0 11.31-4.69L227.31 184H240a16 16 0 0 0 16-16v-48a16 16 0 0 0-16-16m0 64h-16a8 8 0 0 0-5.66 2.34L180.69 208h-77.38L64 168.69V80h116.69l37.65 37.66A8 8 0 0 0 224 120h16Z");
}

</style>
