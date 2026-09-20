<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="azj37obeu"/><path class="j8mnltb8h"/><path class="sd20h8b5i"/><path class="gl36igsyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:broom-outline-regular" /></template>
<style>
.azj37obeu {
  d: path("M12 2v10");
}

.gl36igsyx {
  d: path("M13 12c0.5 3 1 6 1.5 8");
}

.j8mnltb8h {
  d: path("M9 12h6c1 3 2 6 3 8H6c1 -2 2 -5 3 -8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sd20h8b5i {
  d: path("M11 12c-0.5 3 -1 6 -1.5 8");
}

</style>
