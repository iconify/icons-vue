<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yvya64bge"/><path class="kjfqpq08c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fish-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kjfqpq08c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12c2-4 5-7 8-7s5 3 6 5l4-4l-2 6l2 6l-4-4c-1 2-3 5-6 5s-6-3-8-7m5-1h.01M12 10c1 1 1 3 0 4");
}

.yvya64bge {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17.234 8.352l3.059-3.059a1.001 1.001 0 0 1 1.656 1.023L20.054 12l1.895 5.684a1.001 1.001 0 0 1-1.656 1.023l-3.059-3.059C15.878 17.887 13.796 19.999 11 20c-1.92 0-3.662-1.001-5.048-2.26c-1.61-1.465-2.877-3.355-3.846-5.293a1 1 0 0 1 0-.894a21 21 0 0 1 1.755-2.92c1.165-1.612 2.657-3.154 4.481-4.007C9.174 4.236 10.078 4 11 4c2.796.001 4.878 2.113 6.234 4.352");
}

</style>
