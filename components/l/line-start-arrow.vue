<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqywxybaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-arrow" /></template>
<style>
.vqywxybaf {
  fill: currentColor;
  d: path("M13 19L2 12l11-7v6h9v2h-9z");
}

</style>
