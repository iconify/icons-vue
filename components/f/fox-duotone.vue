<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rw9dgi2uo"/><path class="y3-ncereq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rw9dgi2uo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20 9.838l.949 2.846c.119.359.026.755-.242 1.023l-7 7a2.414 2.414 0 0 1-3.414 0l-7-7a1 1 0 0 1-.242-1.023L4 9.838V4a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l3 3C10.02 6.605 10.532 7 11 7h2c.468 0 .98-.395 1.293-.707l3-3c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582Z");
}

.y3-ncereq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 10l1 3l-7 7a1.414 1.414 0 0 1-2 0l-7-7l1-3V4c0-.369.631-.369 1 0l3 3c.64.64 1.36 1 2 1h2c.64 0 1.36-.36 2-1l3-3c.369-.369 1-.369 1 0zM9 12l1 1m5-1l-1 1m-2 3h.01");
}

</style>
