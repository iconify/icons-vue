<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="dysmg9mrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left" /></template>
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

.tx_ah59as {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

</style>
