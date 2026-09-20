<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="ayfcapvsy"/><path class="xios20bld"/><path class="b8bgvry1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:follow-up-review-outline-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ayfcapvsy {
  d: path("M9 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.b8bgvry1b {
  d: path("M12 13h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xios20bld {
  d: path("M12 10v3");
}

</style>
