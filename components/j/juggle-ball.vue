<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ug96i2bfs"/><path class="n3y4dvg4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:juggle-ball" /></template>
<style>
.n3y4dvg4f {
  d: path("m12 5.5l2 1.25L13.25 9h-2.5L10 6.75Zm0 0v-3m2 4.25l2.75-1M13.25 9l1.5 2.75m-4-2.75l-1.5 2.75m.75-5l-2.75-1");
}

.ug96i2bfs {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3.5 21v-5.5h5c1 1.5 2.5 2 4.5 2h4.5c2 0 3 1.25 3 2.5v1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
