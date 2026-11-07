<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wbrcsybpb"/><path class="ukfqk0bhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ukfqk0bhw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4.636 5.636l-1.079.533A1 1 0 0 0 3 7.066v9.868a1 1 0 0 0 .557.897l8 3.95a1 1 0 0 0 .886 0l5.582-2.756M8.423 3.766l3.134-1.547a1 1 0 0 1 .886 0l8 3.95a1 1 0 0 1 .557.897v9.277M3.16 6.523L7.83 8.83M12 13v8.885m2.374-12.168l6.466-3.194M2 3l19 19");
}

.wbrcsybpb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8.423 3.766l3.134-1.547a1 1 0 0 1 .886 0l8 3.95a1 1 0 0 1 .557.897v9.277Zm4.02 18.015a1 1 0 0 1-.886 0l-8-3.95A1 1 0 0 1 3 16.934V7.066a1 1 0 0 1 .557-.897l1.079-.533l13.389 13.389Z");
}

</style>
