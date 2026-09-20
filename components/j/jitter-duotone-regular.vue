<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qqjuc6bqq"/><path class="ex75cacie"/><path class="kyboc-b7u"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jitter-duotone-regular" /></template>
<style>
.ex75cacie {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kyboc-b7u {
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qqjuc6bqq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
