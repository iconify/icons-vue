<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v_8zjeb4n"/><path class="qa_yjoe3f"/><circle class="sapxmnb0l"/><path class="q2ubtvbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jukebox-sharp" /></template>
<style>
.q2ubtvbpa {
  d: path("M9 16v1.75M12 16v1.75M15 16v1.75M7.5 19.5v1.75m9-1.75v1.75");
}

.qa_yjoe3f {
  d: path("M7.5 14v-4a4.5 4.5 0 0 1 9 0v4");
}

.sapxmnb0l {
  cx: 12px;
  cy: 10.5px;
  r: 2px;
}

.v_8zjeb4n {
  d: path("M4.75 10a7.25 7.25 0 0 1 14.5 0v9.5H4.75v-2Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
