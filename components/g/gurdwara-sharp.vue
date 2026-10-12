<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g7ze5yb1u"/><path class="jpou_dbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gurdwara-sharp" /></template>
<style>
.g7ze5yb1u {
  d: path("M3.25 13.5h17.5v7.75H3.25zm4.5 0c0-3 2-4.75 4.25-6.75c2.25 2 4.25 3.75 4.25 6.75Zm-4.5 0v-2.125L5 10.5l1.75.875V13.5Zm14 0v-2.125L19 10.5l1.75.875V13.5ZM12 6.75V3");
}

.jpou_dbqd {
  d: path("M10.5 21.25v-4h3v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
