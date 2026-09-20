<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ywkpxtb5s"/><path class="d9j2xyvdd"/><path class="yvwbi-etd"/><path class="vm7z8yblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:festival-duotone-regular" /></template>
<style>
.d9j2xyvdd {
  d: path("m3 19 9 -9 9 9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vm7z8yblu {
  d: path("m12 3 4 4h-4");
}

.yvwbi-etd {
  d: path("M12 2v8");
}

.ywkpxtb5s {
  fill: currentColor;
  d: path("m3 19 9 -9 9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
