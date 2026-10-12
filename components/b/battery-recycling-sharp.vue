<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wdd_k9f2l"/><path class="sph6zac0d"/><path class="t50rwul0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-recycling-sharp" /></template>
<style>
.sph6zac0d {
  d: path("M9 7.75h6v10H9zm2-2.5h2");
}

.t50rwul0w {
  d: path("M12.6 10.25L11 13h2l-1.6 2.5");
}

.wdd_k9f2l {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
