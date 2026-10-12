<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0eqkvc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-king-sharp" /></template>
<style>
.u0eqkvc-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v4M10.25 4.5h3.5M9 7.75h6l1.397-.004l-.447 1.324L15 11.5v2.333l1.5 1.667h-9L9 13.833V11.5l-.95-2.43l-.447-1.324zm.5 3.75h5m-9.5 7h14v2.75H5z");
}

</style>
