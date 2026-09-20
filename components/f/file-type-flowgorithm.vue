<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="y3d6msbhs"><path transform="matrix(.11086 0 0 .12298 -28.7 0)" class="urqsmc34t"/><path transform="matrix(.11086 0 0 .12298 -28.7 0)" class="f2d5sxv3l"/><path transform="matrix(.11086 0 0 .12298 -28.7 0)" class="oiijmrb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flowgorithm" /></template>
<style>
.f2d5sxv3l {
  fill: var(--svg-color--bddfff, #bddfff);
  stroke: var(--svg-color--172f5f, #172f5f);
  d: path("M325.6 184L298 239.5l182.6.5l27.7-55.9z");
}

.oiijmrb4y {
  fill: var(--svg-color--ffbdbd, #ffbdbd);
  stroke: var(--svg-color--432323, #432323);
  d: path("m403.2 48.8l-119 78.9l119.3 79.5l118.7-79.5z");
}

.urqsmc34t {
  fill: var(--svg-color--ffffbd, #ffffbd);
  stroke: var(--svg-color--3d3d1f, #3d3d1f);
  d: path("M311.2 20h184v56h-184z");
}

.y3d6msbhs {
  stroke-width: var(--svg-stroke-width--8px, 8px);
}

</style>
