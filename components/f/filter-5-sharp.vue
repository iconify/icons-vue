<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nucfay7xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-5-sharp" /></template>
<style>
.nucfay7xu {
  fill: currentColor;
  d: path("M11 14.5h5v-5h-4v-3h4v-1h-5v5h4v3h-4zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
