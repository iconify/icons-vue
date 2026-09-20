<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h9khfxqid"/><path class="bj5ndtr6c"/><path class="hsnj_bbvb"/><path class="hm5wf8bkx"/><path class="t407ddc6o"/><path class="hmleclbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:decoder-duotone-regular" /></template>
<style>
.bj5ndtr6c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h9khfxqid {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 3 -6 6v6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hm5wf8bkx {
  d: path("m20 3 -6 6v6l6 6");
}

.hmleclbdj {
  d: path("m8 9 3 3 -3 3");
}

.hsnj_bbvb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t407ddc6o {
  d: path("M3 12h8");
}

</style>
