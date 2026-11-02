<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qc5ikq90j"/><path class="uihkd04we"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qc5ikq90j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 8a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l3 3a2.414 2.414 0 0 1 0 3.414l-3 3a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 2 16Zm20 0v8c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424l-3-3a2.414 2.414 0 0 1 0-3.414l3-3c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582");
}

.uihkd04we {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V8c0-.369.631-.369 1 0l3 3a1.414 1.414 0 0 1 0 2l-3 3c-.369.369-1 .369-1 0zm9-7v2m0 4v2m0 4v2m9-7V8c0-.369-.631-.369-1 0l-3 3a1.414 1.414 0 0 0 0 2l3 3c.369.369 1 .369 1 0z");
}

</style>
