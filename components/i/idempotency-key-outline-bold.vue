<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="keqc2pbxm"/><path class="tuv2qrbve"/><path class="cq9z3jbol"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idempotency-key-outline-bold" /></template>
<style>
.cq9z3jbol {
  d: path("M12.5 10v3");
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l8vricc3a {
  d: path("M17 10h4");
}

.rjbfcabog {
  d: path("M17 16h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tuv2qrbve {
  d: path("M8 10h7");
}

</style>
