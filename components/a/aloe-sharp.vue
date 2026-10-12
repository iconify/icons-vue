<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sda7shb0x"/><path class="acahw1b7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aloe-sharp" /></template>
<style>
.acahw1b7z {
  d: path("M12 15.5V3.75M9.5 15.5C9 11.75 7.25 9 4.25 7.5m10.25 8c.5-3.75 2.25-6.5 5.25-8M7 15.5l-1.143-1.905l-3.107-.345M17 15.5l1.143-1.905l3.107-.345");
}

.sda7shb0x {
  d: path("M7.75 15.5h9.75l-.27 1.22l-.71 3.31l-.27 1.22h-8.5l-.27-1.22l-.71-3.31l-.27-1.22z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
