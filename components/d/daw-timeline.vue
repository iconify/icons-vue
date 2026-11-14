<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igs5soaez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:daw-timeline" /></template>
<style>
.igs5soaez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h9V7h-9ZM7 10.25h12v3.5H7ZM2.5 17H9v3.5H2.5Zm10 0h9v3.5h-9ZM15 2.5v19");
}

</style>
