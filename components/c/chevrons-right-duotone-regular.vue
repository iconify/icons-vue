<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z17k59bng"/><path class="ttz9q5c2o"/><path class="te2cn0btr"/><path class="pnu4jvbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-right-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pnu4jvbcb {
  d: path("m13 4 8 8 -8 8");
}

.te2cn0btr {
  d: path("m4 4 8 8 -8 8");
}

.ttz9q5c2o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 4 8 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z17k59bng {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 4 8 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
