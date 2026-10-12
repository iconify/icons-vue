<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="amux9pc1h"/><path class="nn5-0kb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checklist-board-sharp" /></template>
<style>
.amux9pc1h {
  d: path("M7.25 7.25L12 2.75l4.75 4.5m-14 0h18.5v14H2.75z");
}

.nn5-0kb5l {
  d: path("m6.25 11.5l1.25 1.25l2.25-2.25m-3.5 6l1.25 1.25l2.25-2.25M12 11.75h5.5m-5.5 5h5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
