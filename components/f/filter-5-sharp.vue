<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlmxwvbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-5-sharp" /></template>
<style>
.jlmxwvbmf {
  fill: currentColor;
  d: path("M11 15h6V9h-4V7h4V5h-6v6h4v2h-4zm-5 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
