<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t37-2fbtz"/><path class="jql8b-n9t"/><path class="xhb4q_tse"/><path class="zhmw1tbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-back-duotone-regular" /></template>
<style>
.jql8b-n9t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t37-2fbtz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhb4q_tse {
  d: path("m10 7 -5 5 5 5");
}

.zhmw1tbis {
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
