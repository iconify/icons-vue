<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lifx7gbih"/><path class="gaabbdbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-gala" /></template>
<style>
.gaabbdbpg {
  d: path("m10.818 3.016l-1.437.226a1.5 1.5 0 0 0-1.218 1.857l1.271 4.926a1.5 1.5 0 0 0 1.577 1.12l.321-.027a1.5 1.5 0 0 0 1.375-1.54l-.155-5.126a1.5 1.5 0 0 0-1.734-1.436M11.25 11l.5 9m-1.5.25l2.861-.477m5.153-4.731l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lifx7gbih {
  d: path("m6.684 3.087l1.666.333a1.5 1.5 0 0 1 1.133 1.931l-1.552 4.814a1.5 1.5 0 0 1-1.792.995l-.428-.107a1.5 1.5 0 0 1-1.133-1.549l.315-5.04a1.5 1.5 0 0 1 1.791-1.377M6 11.25L4.5 20m-2-.25l4 .5");
}

</style>
