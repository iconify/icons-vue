<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwae12bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-road-sharp" /></template>
<style>
.vwae12bzm {
  fill: currentColor;
  d: path("M16 11.664V5h1v5.664zM5 19V5h1v14zm5.5-10.98V5h1v3.02zm0 5.48v-3.02h1v3.02zm0 5.5v-3.02h1V19zm3.73 0v-2.21l5.96-5.934l2.19 2.204L16.44 19zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
