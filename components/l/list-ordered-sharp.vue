<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdf4o6ifl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-ordered-sharp" /></template>
<style>
.rdf4o6ifl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h8m-8 5h8m-8 5h8M4 6l2-2v6m-2 6a2 2 0 1 1 4 0l-4 4h4");
}

</style>
