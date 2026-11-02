<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zngn3pqim"/><path class="hzwt2gyyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:framer-duocolor-sharp" /></template>
<style>
.hzwt2gyyp {
  d: path("M12 9L6 3h12v6zm-6 6h6v6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zngn3pqim {
  stroke-opacity: 0.4;
  d: path("m12 9l6 6H6V9m0 0h6");
}

</style>
