<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtk93b_xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive" /></template>
<style>
.jtk93b_xn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H5a2 2 0 0 1-2-2v-4l3-6c.613-1.226 1.387-2 2-2h8c.613 0 1.387.774 2 2l3 6v4a2 2 0 0 1-2 2zm-9-6h18M7 16h.01M11 16h.01");
}

</style>
