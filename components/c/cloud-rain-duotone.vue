<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_hti76ob"/><path class="j9tli0b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-duotone" /></template>
<style>
.j9tli0b-m {
  d: path("M8 20L8 22M12 20L12 22M16 20L16 22");
}

.n_hti76ob {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 17L18 17C20.5784 17 22.734 15.0393 22.9776 12.4724C23.2212 9.9055 21.4729 7.5743 18.9405 7.0893C18.4833 3.6052 15.5139 1 12 1C8.4861 1 5.5167 3.6052 5.0595 7.0893C2.5271 7.5743 0.7788 9.9055 1.0224 12.4724C1.266 15.0393 3.4216 17 6 17Z");
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
