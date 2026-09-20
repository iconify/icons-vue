<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7d250moc"/><path class="jlpxneb5g"/><path class="shqn1eeqv"/><path class="a4s69abac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breakpoint-log-outline-regular" /></template>
<style>
.a4s69abac {
  d: path("M12 14h9");
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.n7d250moc {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shqn1eeqv {
  d: path("M12 10h9");
}

</style>
