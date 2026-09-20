<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnvcx7b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-group-outline-sharp" /></template>
<style>
.xnvcx7b1r {
  fill: currentColor;
  d: path("M7.5 16h12V6h-12zm-1 1V3h14v14zm-3 3V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
