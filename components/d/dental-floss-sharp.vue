<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kotzdktgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dental-floss-sharp" /></template>
<style>
.kotzdktgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.5h12.5v12.75H3.75zm0 4.25h12.5M10 8.5v-2C10 4.25 11.5 3 13.25 3C15.5 3 16 5.5 18 5.5h1.667l.833-1.25");
}

</style>
