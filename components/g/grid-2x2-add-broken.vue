<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="taogqpb9g"/><path class="mm6j7bb6p"/><path class="noodpccbe"/><path class="y2cuq6b_i"/><path class="c8yuot4zz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-add-broken" /></template>
<style>
.c8yuot4zz {
  d: path("M14.5 17.5H17.5M17.5 17.5H20.5M17.5 17.5V14.5M17.5 17.5V20.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mm6j7bb6p {
  d: path("M21.9996 11.9999C21.9996 7.28584 21.9996 4.92882 20.5352 3.46436");
}

.noodpccbe {
  d: path("M22 12H10M6 12H2");
}

.taogqpb9g {
  d: path("M16.5501 2.08856C15.3375 2 13.8503 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22");
}

.y2cuq6b_i {
  d: path("M12.0049 22.0049V2.00488");
}

</style>
