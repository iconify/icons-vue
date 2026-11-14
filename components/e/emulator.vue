<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j9oj0xj6k"/><path class="vjzi9_byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emulator" /></template>
<style>
.j9oj0xj6k {
  d: path("M12.2 15H2.5V3h17v5.2M11 15v4m-4 0h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjzi9_byq {
  d: path("m5.5 6l2 2l-2 2m4 0H12m3 1h6.5v11H15Z");
}

</style>
