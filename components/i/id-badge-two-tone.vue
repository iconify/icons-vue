<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fef3h-tyk"/><path class="dqwu__trf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-badge-two-tone" /></template>
<style>
.dqwu__trf {
  d: path("M8 2L16 2C17.6569 2 19 3.3431 19 5L19 19C19 20.6569 17.6569 22 16 22L8 22C6.3431 22 5 20.6569 5 19L5 5C5 3.3431 6.3431 2 8 2ZM10 6L14 6M14 13C14 14.1046 13.1046 15 12 15C10.8954 15 10 14.1046 10 13C10 11.8954 10.8954 11 12 11C13.1046 11 14 11.8954 14 13ZM8 22C8 20.3431 9.3432 19 11 19L13 19C14.6569 19 16 20.3431 16 22");
}

.fef3h-tyk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 1C18.2092 1 20 2.79082 20 5V19C20 21.2092 18.2092 23 16 23H8C5.79082 23 4 21.2092 4 19V5C4 2.79082 5.79082 1 8 1H16Z");
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
