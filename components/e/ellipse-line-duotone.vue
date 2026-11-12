<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="md2jkknwk"/><path class="h75i1lw9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ellipse-line-duotone" /></template>
<style>
.h75i1lw9a {
  stroke-linecap: round;
  d: path("M17.7351 6.265C16.1114 5.468 14.1338 5 12 5C6.4772 5 2 8.134 2 12C2 14.372 3.6859 16.469 6.2649 17.735");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md2jkknwk {
  d: path("M22 12C22 15.866 17.5228 19 12 19C6.47715 19 2 15.866 2 12C2 8.13401 6.47715 5 12 5C17.5228 5 22 8.13401 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
