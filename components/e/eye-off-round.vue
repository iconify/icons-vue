<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd0ookesy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-round" /></template>
<style>
.cd0ookesy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.76 16.76A9.75 9.75 0 0 1 3 12a9.74 9.74 0 0 1 4.24-4.76M12 6a9.75 9.75 0 0 1 9 6a9.8 9.8 0 0 1-1.073 1.927m-9.341-3.341a2 2 0 1 0 2.828 2.828M2 2l20 20");
}

</style>
