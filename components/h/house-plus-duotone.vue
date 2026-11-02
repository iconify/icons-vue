<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jbyvjlb7k"/><path class="z7ivvrggm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-plus-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jbyvjlb7k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 22H6a3 3 0 0 1-3-3v-7c0-1.039.578-1.992 1.293-2.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6C20.422 10.008 21 10.961 21 12v7a3 3 0 0 1-3 3");
}

.z7ivvrggm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 7l3 3c.64.64 1 1.36 1 2v7a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-7c0-.64.36-1.36 1-2l6-6a1.414 1.414 0 0 1 2 0zm-7 7h6m-3-3v6");
}

</style>
