<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e9iocqotb"/><path class="s-i3zxb3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bear-duotone" /></template>
<style>
.e9iocqotb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 9C3.004 6.33 6.996 3.336 9 6c1.992-.995 4.008-.995 6 0c2.004-2.664 5.996.33 4 3c2 3 2 6 1 8c-1.143 3.421-4.852 3.999-8 4c-3.148-.001-6.857-.579-8-4c-1-2-1-5 1-8");
}

.ft5dv1b6b {
  fill: none;
}

.s-i3zxb3b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9C3 6.333 7 3.333 9 6q3-1.5 6 0c2-2.667 6 .333 4 3c2 3 2 6 1 8c-1 3-4 4-8 4s-7-1-8-4c-1-2-1-5 1-8m4 3h.01M15 12h.01M11 16h2l-1 1Z");
}

</style>
