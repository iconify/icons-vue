<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cop6wg96p"/><path class="ks6rcsblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-image" /></template>
<style>
.cop6wg96p {
  d: path("M14 2H8C5.79086 2 4 3.79086 4 6V18C4 20.2091 5.79086 22 8 22H16C18.2091 22 20 20.2091 20 18V8L14 2ZM14 2V5C14 6.65685 15.3431 8 17 8H20M4 18L9.2355 12.7645C9.6921 12.3079 10.3895 12.1948 10.967 12.4835L20 17");
}

.ks6rcsblm {
  fill: currentColor;
  d: path("M10.5 7C10.5 7.8284271247 9.8284271247 8.5 9 8.5C8.1715728753 8.5 7.5 7.8284271247 7.5 7C7.5 6.1715728753 8.1715728753 5.5 9 5.5C9.8284271247 5.5 10.5 6.1715728753 10.5 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
