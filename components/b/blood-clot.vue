<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u45xnhbml"/><path class="amcujv1an"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-clot" /></template>
<style>
.amcujv1an {
  fill: currentColor;
  d: path("M9 8c1.5-1 3 .25 4-.25c1.5-.75 3 .5 2.75 2.25c1.25 1 1 3.25-.25 4c.5 1.75-1.25 2.75-2.5 2.25c-1.25.75-3 .25-3.5-1c-1.5-.5-2-2.5-1-3.5C7.5 10.5 7.75 8.5 9 8Z");
}

.u45xnhbml {
  d: path("M2.5 5.5h19m-19 13h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
