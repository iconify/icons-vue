<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ith8ou_qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-sharp" /></template>
<style>
.ith8ou_qc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6H3v15h10V11M8 6l5 5M8 6v5h5m-2-8h5m0 0l5 5m-5-5v5h5m0 0v10h-4");
}

</style>
