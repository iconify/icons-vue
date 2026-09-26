<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vh0pyof4v"/><path class="dysmg9mrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left-duotone" /></template>
<style>
.dysmg9mrs {
  d: path("M7.27326 12.4699L15.2107 16.9316C15.5648 17.1306 16 16.8716 16 16.4617V7.5383C16 7.12844 15.5648 6.86937 15.2107 7.06842L7.27326 11.5301C6.90891 11.7349 6.90891 12.2651 7.27326 12.4699Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vh0pyof4v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 12C1 18.0751 5.92487 23 12 23C18.0751 23 23 18.0751 23 12C23 5.92487 18.0751 1 12 1C5.92487 1 1 5.92487 1 12Z");
  stroke: none;
}

</style>
