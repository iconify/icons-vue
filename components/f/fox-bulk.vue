<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ppk140b9i"/><path class="u-t2g1brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ppk140b9i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l3 3C10.02 6.605 10.532 7 11 7h2c.468 0 .98-.395 1.293-.707l3-3c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v5.838l.949 2.846c.119.359.026.755-.242 1.023l-7 7a2.414 2.414 0 0 1-3.414 0l-7-7a1 1 0 0 1-.242-1.023L4 9.838Z");
}

.u-t2g1brr {
  d: path("M10.707 12.293a.999.999 0 1 1-1.414 1.414l-1-1a.999.999 0 1 1 1.414-1.414Zm4 1.414a.999.999 0 1 1-1.414-1.414l1-1a.999.999 0 1 1 1.414 1.414ZM12.01 15a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
