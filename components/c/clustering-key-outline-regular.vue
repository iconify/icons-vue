<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="t87ohzbeq"/><path class="tkgsjrp5m"/><path class="okg0-qwlz"/><path class="t-6-epb6g"/><path class="vvb9xqkys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clustering-key-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okg0-qwlz {
  d: path("M4.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t-6-epb6g {
  d: path("M4.5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

.tkgsjrp5m {
  d: path("M4.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vvb9xqkys {
  d: path("M12 12h7");
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
