<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej3jcybeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:factory-sharp" /></template>
<style>
.ej3jcybeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V11.5l.83-.55l3.59-2.4L8 8v3.5l.83-.55l3.59-2.4l.83-.55v3.5l.83-.55l.59-.4l.83-.55V2.75h5.75v18.5H2.75zm3.5-4h2m2.75 0h2m2.75 0h2");
}

</style>
