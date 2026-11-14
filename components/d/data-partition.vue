<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hvd--9t6q"/><path class="cqq5dub7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-partition" /></template>
<style>
.cqq5dub7n {
  d: path("M7.5 8v12.5H5a2 2 0 0 1-2-2V8m7.5 0v12.5h3V8m3 0v12.5H19a2 2 0 0 0 2-2V8M3 14.25h4.5m3 0h3m3 0H21");
}

.hvd--9t6q {
  fill: currentColor;
  d: path("M3 8V5.5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2V8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
