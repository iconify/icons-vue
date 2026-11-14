<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rqmrnye1z"/><path class="yg_3e-big"/><path class="h7jf_xb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-flowers" /></template>
<style>
.h7jf_xb_f {
  d: path("M12.5 13.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-6 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 7V21");
}

.rqmrnye1z {
  d: path("M10 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yg_3e-big {
  d: path("M9.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.5 4a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
