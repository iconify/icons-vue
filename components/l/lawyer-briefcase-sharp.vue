<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fjehvrbpc"/><path class="i1fgvobac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lawyer-briefcase-sharp" /></template>
<style>
.fjehvrbpc {
  d: path("M2.75 7.25h18.5v13.5H2.75zm6 0v-3.5h6.5v3.5");
}

.i1fgvobac {
  d: path("M12 10.75v6.5m-1.75 0h3.5M8 12h8m-8 0l-1.25 2.75h2.5Zm8 0l-1.25 2.75h2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
