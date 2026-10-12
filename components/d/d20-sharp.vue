<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh1av6b5y"/><path class="ov229mbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:d20-sharp" /></template>
<style>
.bh1av6b5y {
  d: path("m13.3 3.5l5.4 3.13l1.3.75v9.25l-1.3.75l-5.4 3.12l-1.3.75l-1.3-.75l-5.4-3.12l-1.3-.75V7.38l1.3-.75l5.4-3.13l1.3-.75z");
}

.ov229mbvy {
  d: path("m12.38 8.14l3.99 6.72l.38.64h-9.5l.38-.64l3.99-6.72l.38-.64zM12 7.5v-4m-4.75 12L4.6 17m12.15-1.5L19.4 17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
