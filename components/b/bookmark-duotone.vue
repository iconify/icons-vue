<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n4ovsc7im"/><path class="tpz6jzwjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n4ovsc7im {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 3a3 3 0 0 1 3 3v12c0 .285-.076.563-.225.806c-.624 1.009-2.073.939-3.064.629a4.9 4.9 0 0 1-1.266-.603L12 17.202l-2.445 1.63a4.9 4.9 0 0 1-1.266.603c-.991.31-2.44.38-3.064-.629A1.54 1.54 0 0 1 5 18V6a3 3 0 0 1 3-3Z");
}

.tpz6jzwjb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h4a2 2 0 0 1 2 2v12c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6a2 2 0 0 1 2-2z");
}

</style>
