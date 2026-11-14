<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kojyvzb0i"/><path class="wzmxe4eit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:highlighter" /></template>
<style>
.kojyvzb0i {
  d: path("m16.596 3.161l4.243 4.243l-7.425 7.424l-4.242-4.242Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzmxe4eit {
  d: path("m9.172 10.586l4.242 4.242l-2.828 1.415l-2.829-2.829Zm-1.061 3.182l2.121 2.121l-1.06 1.061l-3.182-1.061ZM3 21h6.5");
}

</style>
