<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t6_d45yfx"/><path class="olvjgvbfj"/><path class="k67_umbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chapel-bell-gable" /></template>
<style>
.k67_umbik {
  d: path("M12 9.5v2M9.5 16v-2a2.5 2.5 0 0 1 5 0v2l.75 1h-6.5zm2.5 3.25h.01");
}

.olvjgvbfj {
  d: path("M6.5 21.5V15a5.5 5.5 0 0 1 11 0v6.5");
}

.t6_d45yfx {
  d: path("M3 21.5V11l9-6l9 6v10.5M12 2v3m-1.5-1.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
