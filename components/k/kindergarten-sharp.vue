<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yh-m50bvw"/><path class="gx6jmrbif"/><path class="jbo4_npny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kindergarten-sharp" /></template>
<style>
.gx6jmrbif {
  d: path("M3.75 13v-1l.8-.6l6.25-4.7l1.2-.9l1.2.9l6.25 4.7l.8.6v9.25H3.75v-2Z");
}

.jbo4_npny {
  d: path("M10.5 21.25v-4.5h3v4.5M7 15h1.5m7 0H17m-6.75-1.75h3.5m-3 0v-2.5h2.5v2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yh-m50bvw {
  d: path("M12 6.3V2.75h3.25L14.5 4l.75 1.25H12");
}

</style>
