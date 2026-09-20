<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdjp1t81b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-plus" /></template>
<style>
.mdjp1t81b {
  fill: currentColor;
  d: path("M16 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zm-8 0q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V2h4v2h2q.425 0 .713.288T17 5v7q-.2 0-.4.013t-.4.037q-2.2.3-3.7 1.975T11 18q0 1.125.4 2.15T12.525 22z");
}

</style>
