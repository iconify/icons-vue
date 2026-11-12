<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awqrxe9oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-sharp" /></template>
<style>
.awqrxe9oo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9h6v6H9ZM3 7V3h4m4 0h4v2M3 11v4h2m14-6h2v4m0 4v4h-4m-8-2v2h4");
}

</style>
