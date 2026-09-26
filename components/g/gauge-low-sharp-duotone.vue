<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t8drw368i"/><path class="fdmkd28lk"/><path class="ivtq_i9rl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gauge-low-sharp-duotone" /></template>
<style>
.fdmkd28lk {
  d: path("M12 12L8.1716 8.1716");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ivtq_i9rl {
  fill: currentColor;
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12ZM7 12C7 12.5523 6.5523 13 6 13C5.4477 13 5 12.5523 5 12C5 11.4477 5.4477 11 6 11C6.5523 11 7 11.4477 7 12ZM13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM17.2426 7.7574C17.2426 8.3096 16.7949 8.7574 16.2426 8.7574C15.6904 8.7574 15.2426 8.3096 15.2426 7.7574C15.2426 7.2051 15.6904 6.7574 16.2426 6.7574C16.7949 6.7574 17.2426 7.2051 17.2426 7.7574ZM19 12C19 12.5523 18.5523 13 18 13C17.4477 13 17 12.5523 17 12C17 11.4477 17.4477 11 18 11C18.5523 11 19 11.4477 19 12Z");
  stroke: none;
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
