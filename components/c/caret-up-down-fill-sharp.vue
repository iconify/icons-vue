<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lckrnrbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-up-down-fill-sharp" /></template>
<style>
.lckrnrbpj {
  fill: currentColor;
  d: path("M11.293 5.293a1 1 0 0 1 1.414 0l4 4A1 1 0 0 1 16 11H8a1.002 1.002 0 0 1-.707-1.707Zm5.414 9.414l-4 4a1 1 0 0 1-1.414 0l-4-4A1 1 0 0 1 8 13h8a1.002 1.002 0 0 1 .707 1.707");
}

</style>
