<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1q_jvb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-sharp" /></template>
<style>
.i1q_jvb4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17c7 4 13-1 12-12C8 4 3 10 7 17m-1 3c.1-.7.4-1.8 1-3m0 0c1.6-2.4 3.4-4.4 6-6");
}

</style>
