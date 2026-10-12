<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jz9q7xblp"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:galaxy-sharp" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.jz9q7xblp {
  d: path("M12 8.5c.3-.05 1.15-.38 1.78-.32l1.148.091l.852.559l1.1.692l.58 1.018l.734 1.241l.086 1.329l.105 1.609l-.575 1.351l-.671 1.617l-1.229 1.083l-1.481 1.272l-1.689.458c-1.17.32-3.25.16-3.9.19M12 15.5c-.3.05-1.15.38-1.78.32l-1.148-.091l-.852-.559l-1.1-.692l-.58-1.018l-.734-1.241l-.086-1.329l-.105-1.609l.575-1.351l.671-1.617L8.09 5.23l1.481-1.272L11.26 3.5c1.17-.32 3.25-.16 3.9-.19");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
