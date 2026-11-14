<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bbre26b5k"/><path class="muar-0brj"/><path class="rmjy0xbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation-history" /></template>
<style>
.bbre26b5k {
  d: path("M11.462 18.429H9.435l-.198-2.063l-1.992-.825l-1.598 1.319l-1.507-1.507l1.319-1.598l-.825-1.992l-2.063-.198v-2.13l2.063-.198l.825-1.992L4.14 5.647L5.647 4.14l1.598 1.319l1.992-.825l.198-2.063h2.13l.198 2.063l1.992.825l1.598-1.319l1.507 1.507l-1.319 1.598l.825 1.992l2.063.198V11.5");
}

.muar-0brj {
  d: path("M7.75 10.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm6.5 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.rmjy0xbjb {
  d: path("M18 16.75V18l1.25.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
