<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g3q6u4oio"/><path class="o41j5dbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:archaeology-brush" /></template>
<style>
.g3q6u4oio {
  d: path("m18.718 5.282l-4.95 4.95m-2.122-2.121l4.243 4.243l-2.121 2.121l-4.243-4.243Z");
}

.o41j5dbaw {
  d: path("m9.525 10.232l4.243 4.243l-5.304 6.717l-5.656-5.656Zm0 4.243l-3.889 3.889");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
