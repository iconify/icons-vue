<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf9mk6-qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-1-sharp" /></template>
<style>
.tf9mk6-qv {
  fill: currentColor;
  d: path("M14 15h2V5h-4v2h2zm-8 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
