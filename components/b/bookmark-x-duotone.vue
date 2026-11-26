<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eji0i44qv"/><path class="p2ybn-bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-x-duotone" /></template>
<style>
.eji0i44qv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5C3 2.7909 4.7909 1 7 1L10 1C10.5523 1 11 1.4477 11 2L11 8C11 9.6569 12.3431 11 14 11L20 11C20.5523 11 21 11.4477 21 12L21 20.9983C20.9987 22.1027 20.1031 22.9972 18.9987 22.9972C18.6158 22.9972 18.2409 22.8874 17.9185 22.6807L12.2704 19.6926C12.1057 19.5867 11.8943 19.5867 11.7296 19.6926L6.0815 22.6807C5.7591 22.8874 5.3842 22.9972 5.0013 22.9972C3.8969 22.9972 3.0013 22.1027 3 20.9983Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2ybn-bak {
  d: path("M14 2L20 8M20 2L14 8");
}

</style>
