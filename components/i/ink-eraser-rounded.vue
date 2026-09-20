<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi6rd4b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-eraser-rounded" /></template>
<style>
.hi6rd4b3o {
  fill: currentColor;
  d: path("M16.712 18h4.173q.213 0 .356.143t.144.357t-.144.357t-.356.143H15.71zM4.887 19q-.162 0-.301-.056q-.14-.055-.27-.186l-1.172-1.171q-.479-.48-.491-1.137t.466-1.161L13.273 4.733q.479-.503 1.134-.494t1.133.489l4.09 4.09q.48.479.49 1.146q.009.668-.47 1.146l-7.446 7.647q-.131.13-.28.186t-.31.056z");
}

</style>
