<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a88uu03mv"/><path class="t2ol77uke"/><path class="fpogunu_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-radial-bar" /></template>
<style>
.a88uu03mv {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12");
}

.fpogunu_q {
  d: path("M12 9a3 3 0 0 1 2.819 4.026");
}

.t2ol77uke {
  d: path("M12 5.75a6.25 6.25 0 1 1-2.138 12.123");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
