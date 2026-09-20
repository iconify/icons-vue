<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv0d6ybtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-2-sharp" /></template>
<style>
.dv0d6ybtl {
  fill: currentColor;
  d: path("M11 15h6v-2h-4v-2h4V5h-6v2h4v2h-4zm-5 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
