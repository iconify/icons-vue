<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><circle class="mcpohmiso"/><path class="hassfqb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-card-sharp" /></template>
<style>
.fha6990wp {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.hassfqb7w {
  d: path("m5.75 16l.769-2h3.962l.769 2M14 10h3.75M14 13.5h2.5");
}

.mcpohmiso {
  cx: 8.5px;
  cy: 10.5px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
