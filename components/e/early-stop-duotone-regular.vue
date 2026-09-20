<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w0pt91byz"/><path class="dbfzjzb3n"/><path class="gh1l41bbm"/><path class="t3rq50btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:early-stop-duotone-regular" /></template>
<style>
.dbfzjzb3n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gh1l41bbm {
  d: path("m3 5 6 6h4l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t3rq50btb {
  d: path("M19 4v16");
}

.w0pt91byz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 5 6 6h4l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
