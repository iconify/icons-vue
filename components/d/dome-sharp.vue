<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b958zdbvp"/><path class="jy2yxpbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dome-sharp" /></template>
<style>
.b958zdbvp {
  d: path("M5.25 16.5a6.75 7.5 0 0 1 13.5 0Z");
}

.jy2yxpbcp {
  d: path("m12 9l-2.75 3.143V16.5M12 9l2.75 3.143V16.5m-4-11h2.5V9h-2.5zm1.25 0V2.75M4.25 16.5h15.5v4.75H4.25zm5.25 1.75v1.5m5-1.5v1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
