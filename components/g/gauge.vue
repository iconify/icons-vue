<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dglxlpk3o"/><path class="fxypyjbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gauge" /></template>
<style>
.dglxlpk3o {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12ZM12 12L12 7");
}

.fxypyjbih {
  fill: currentColor;
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12ZM7 12C7 12.5523 6.5523 13 6 13C5.4477 13 5 12.5523 5 12C5 11.4477 5.4477 11 6 11C6.5523 11 7 11.4477 7 12ZM8.7574 7.7574C8.7574 8.3096 8.3096 8.7574 7.7574 8.7574C7.2051 8.7574 6.7574 8.3096 6.7574 7.7574C6.7574 7.2051 7.2051 6.7574 7.7574 6.7574C8.3096 6.7574 8.7574 7.2051 8.7574 7.7574ZM17.2426 7.7574C17.2426 8.3096 16.7949 8.7574 16.2426 8.7574C15.6904 8.7574 15.2426 8.3096 15.2426 7.7574C15.2426 7.2051 15.6904 6.7574 16.2426 6.7574C16.7949 6.7574 17.2426 7.2051 17.2426 7.7574ZM19 12C19 12.5523 18.5523 13 18 13C17.4477 13 17 12.5523 17 12C17 11.4477 17.4477 11 18 11C18.5523 11 19 11.4477 19 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
