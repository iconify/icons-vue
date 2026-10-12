<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mg7w6vb1w"/><path class="g0j2u5bfj"/><path class="j4w0kd-jm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laurel-wreath-sharp" /></template>
<style>
.g0j2u5bfj {
  d: path("m16.52 17.27l1.71 1.44l1.61-1.56l-1.71-1.44zm1.9-2.93l2.21.39l.61-2.16l-2.2-.39zm.18-3.49l2.11-.77l-.54-2.17l-2.11.76zm-1.58-3.12l1.44-1.71l-1.56-1.61l-1.44 1.71zM9.69 18.59a6.75 6.75 0 0 1-.86-12.3");
}

.j4w0kd-jm {
  d: path("m7.48 17.27l-1.61-1.56l-1.71 1.44l1.61 1.56zm-1.9-2.93l-.62-2.16l-2.2.39l.61 2.16zm-.18-3.49l.54-2.18l-2.11-.76l-.54 2.17zm1.58-3.12l1.56-1.61L7.1 4.41L5.54 6.02zm1.77 13.52L12 19l3.25 2.25");
}

.mg7w6vb1w {
  d: path("M14.31 18.59a6.75 6.75 0 0 0 .86-12.3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
