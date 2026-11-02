<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd35xubrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-fill" /></template>
<style>
.zd35xubrg {
  fill: currentColor;
  d: path("M13.707 21.707a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0l8 8a2.414 2.414 0 0 1 0 3.414Z");
}

</style>
