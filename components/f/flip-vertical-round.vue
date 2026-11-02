<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvs2kr1fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-round" /></template>
<style>
.pvs2kr1fr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3H9c-.738 0-1.369.631-1 1l3 3a1.414 1.414 0 0 0 2 0l3-3c.369-.369-.262-1-1-1zm-7 9h2m4 0h2m4 0h2m-7 9H9c-.738 0-1.369-.631-1-1l3-3a1.414 1.414 0 0 1 2 0l3 3c.369.369-.262 1-1 1z");
}

</style>
