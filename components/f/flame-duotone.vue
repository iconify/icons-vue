<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cqjr26qps"/><path class="bus8ftb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-duotone" /></template>
<style>
.bus8ftb2b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3c.5 2.5 2 4.5 4 6c1.5 1.5 2 3.5 2 6a6 6 0 1 1-12 0c0-1.5.5-2.5 1-3m0 0a2 2 0 1 0 4 0c0-1.5-.5-2-1-3c-1-2-.5-4 2-6");
}

.cqjr26qps {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14.262 5.808c.635.925 1.442 1.72 2.338 2.392a1 1 0 0 1 .107.093a7.4 7.4 0 0 1 1.81 3.034c.37 1.184.483 2.438.483 3.673a7.002 7.002 0 0 1-14 0c0-1.302.345-2.758 1.293-3.707A.999.999 0 0 1 8 12a.997.997 0 0 0 1 1a1 1 0 0 0 .707-.293A1 1 0 0 0 10 12c0-.365-.035-.737-.152-1.085c-.1-.298-.26-.579-.413-.853a17 17 0 0 1-.329-.615c-1.451-2.903-.063-5.361 2.269-7.228a1.002 1.002 0 0 1 1.606.585a8 8 0 0 0 1.281 3.004");
}

.ft5dv1b6b {
  fill: none;
}

</style>
