<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="amzf-x08v"/><path clip-rule="evenodd" class="gr9eq7b1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-sharp-duotone" /></template>
<style>
.amzf-x08v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.5 9.1338C21.8095 9.3124 22.0002 9.6426 22 10L22 20C22 20.5523 21.5523 21 21 21L17.5 21C17.0411 21 16.6411 20.6877 16.5299 20.2425L16.2192 19L7.7808 19L7.4701 20.2425C7.3589 20.6877 6.9589 21 6.5 21L3 21C2.4477 21 2 20.5523 2 20L2 10C1.9998 9.6426 2.1905 9.3124 2.5 9.1338L2.5 8L4.693 8L6.5812 3.6052C6.739 3.238 7.1003 3 7.5 3L16.5 3C16.8997 3 17.261 3.238 17.4188 3.6053L19.3069 8L21.5 8L21.5 9.1338Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gr9eq7b1x {
  fill-rule: evenodd;
  d: path("M6.4402 9L8.1587 5L15.8413 5L17.5598 9L6.4402 9ZM9 12.5L9 15.5L7 15.5L7 12.5L9 12.5ZM17 12.5L17 15.5L15 15.5L15 12.5L17 12.5Z");
}

</style>
