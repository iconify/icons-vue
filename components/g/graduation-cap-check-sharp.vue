<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p4_csjcqu"/><path class="suxx-db8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graduation-cap-check-sharp" /></template>
<style>
.p4_csjcqu {
  d: path("m12.89 5.21l7.47 3.83l.89.46l-.89.46l-7.47 3.83l-.89.46l-.89-.46l-7.47-3.83l-.89-.46l.89-.46l7.47-3.83l.89-.46z");
}

.suxx-db8r {
  d: path("M6.5 11.75v4.5C6.5 18 9 19.5 12 19.5s5.5-1.5 5.5-3.25v-4.5m2.75-1.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
