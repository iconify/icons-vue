<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_hti76ob"/><path class="sf7f9yjnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-two-tone" /></template>
<style>
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

.sf7f9yjnt {
  d: path("M6 16L18 16C20.2091 16 22 14.2091 22 12C22 9.7909 20.2091 8 18 8C18 4.6863 15.3137 2 12 2C8.6863 2 6 4.6863 6 8C3.7909 8 2 9.7909 2 12C2 14.2091 3.7909 16 6 16ZM8 20V22M12 20V22M16 20V22");
}

</style>
