<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t8drw368i"/><path class="ox_05kl4h"/><path class="eafkbe28z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-seven-eighth-two-tone" /></template>
<style>
.eafkbe28z {
  fill: currentColor;
  d: path("M7.0502 16.9498C5.7846 15.6841 5 13.9328 5 12C5 10.1435 5.7375 8.363 7.0503 7.0503C7.2379 6.8627 7.4922 6.7574 7.7574 6.7574C8.0226 6.7574 8.277 6.8628 8.4645 7.0503L11 9.5858L11 6C11 5.4477 11.4477 5 12 5C15.8661 5 19 8.1339 19 12C19 15.8661 15.8661 19 12 19C10.0672 19 8.3159 18.2154 7.0502 16.9498Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox_05kl4h {
  d: path("M12 2C17.5228 2 22 6.4772 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2Z");
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
