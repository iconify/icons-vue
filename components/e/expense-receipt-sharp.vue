<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x1tn84b0m"/><path class="z7q7zsbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:expense-receipt-sharp" /></template>
<style>
.x1tn84b0m {
  d: path("M5.85 2.75h12.9v18.5l-.5-.33l-1.25-.84l-.5-.33l-.5.33l-1.25.84l-.5.33l-.5-.33l-1.25-.84l-.5-.33l-.5.33l-1.25.84l-.5.33l-.5-.33L8 20.08l-.5-.33l-.5.33l-1.25.84l-.5.33V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7q7zsbbc {
  d: path("m13.93 10.08l-.488-1.22H10.09v1.5c0 1.99 4.02 1.12 4.02 3.25v1.54h-3.59l-.61-1.22M12 7.63v1.22m0 6.3v1.22");
}

</style>
