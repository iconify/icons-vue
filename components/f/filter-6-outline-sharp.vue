<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc_pebceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-6-outline-sharp" /></template>
<style>
.nc_pebceo {
  fill: currentColor;
  d: path("M12 9.5v-3h3v-1h-4v9h5v-5zm0 1h3v3h-3zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
