<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wsird7b6w"/><path class="lob-p4n4f"/><path class="rk3avflyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:investment-goal-outline-regular" /></template>
<style>
.lob-p4n4f {
  d: path("M18 5v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rk3avflyg {
  d: path("M18 6h4v3.5h-4");
}

.wsird7b6w {
  d: path("m2 21 5 -5 4 4 7 -7 4 4");
}

</style>
