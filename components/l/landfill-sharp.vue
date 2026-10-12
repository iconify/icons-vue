<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw2aeccfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:landfill-sharp" /></template>
<style>
.mw2aeccfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.27 19.84l2.21-5.93L6 12.5h12l.52 1.41l2.21 5.93l.52 1.41H2.75zm-.52 1.41h18.5M9.2 12l-.65-7l-.05-.5h7l-.05.5l-.65 7l-.05.5h-5.5zM7.25 4.5h9.5M12 6.75v3.5");
}

</style>
