<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr87vet0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-split-sharp" /></template>
<style>
.dr87vet0p {
  fill: currentColor;
  d: path("M3 19v-6h18v6zm0-8V9h18v2zm0-4V5h18v2z");
}

</style>
