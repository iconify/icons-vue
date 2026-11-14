<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_4xf-bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coloring-book" /></template>
<style>
.j_4xf-bif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 11.16V4.5c-3-.5-6.5 0-9 1.5c-2.5-1.5-6-2-9-1.5v14c2.275-.379 4.838-.183 7.033.588M12 6v10.4m1.611 2.368l3.889-3.889l2.828-.707L19.621 17l-3.889 3.889Z");
}

</style>
