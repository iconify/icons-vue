<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_ssmh9ez"/><path class="h2-2dgnfu"/><path class="c1g3vxf2c"/><path class="o9gvf5b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:basketball-outline-regular" /></template>
<style>
.c1g3vxf2c {
  d: path("M5 6c3 3 3 9 0 12");
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.o9gvf5b1t {
  d: path("M19 6c-3 3 -3 9 0 12");
}

</style>
