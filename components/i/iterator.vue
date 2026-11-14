<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k_y2xpwaa"/><path class="u95zk4bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:iterator" /></template>
<style>
.k_y2xpwaa {
  d: path("M16 5.072a8 8 0 1 1-8 0");
}

.u95zk4bjs {
  d: path("m5.25 4.25l3 .75l-.75 3M9 12h.01M12 12h.01M15 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
