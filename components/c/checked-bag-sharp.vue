<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbg_vsbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checked-bag-sharp" /></template>
<style>
.sbg_vsbyl {
  fill: currentColor;
  d: path("M8.5 17V6H9q0-1.25.875-2.125T12 3t2.125.875T15 6h.5v11zm2-11h3q0-.65-.425-1.075T12 4.5t-1.075.425T10.5 6M17 17V6h3v11zM4 17V6h3v11zm-2 4v-2h20v2z");
}

</style>
