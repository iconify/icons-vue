<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwwb8k8on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:library-fill-round" /></template>
<style>
.gwwb8k8on {
  fill: currentColor;
  d: path("M7 2v20H6a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Zm2 0h1c1.188 0 2.263.697 2.743 1.784l3.014-.754a1 1 0 0 1 1.213.727l4 16a1 1 0 0 1-.727 1.213l-4 1a1 1 0 0 1-1.213-.727L13 13.123V19a3 3 0 0 1-3 3H9Z");
}

</style>
