<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1pa2hbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-4-outline-sharp" /></template>
<style>
.i1pa2hbit {
  fill: currentColor;
  d: path("M6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4zm7-1h2V5h-2v4h-2V5h-2v6h4z");
}

</style>
