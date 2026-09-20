<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3vqkwb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-land-outline-sharp" /></template>
<style>
.d3vqkwb0g {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm14.223-4.82L4 11.045V5.02l1.458.425l1.122 3.32l4.084 1.187l-.817-8.19l1.856.542l2.988 8.821l4.262 1.244q.452.143.749.523q.297.381.297.864q0 .644-.52 1.143t-1.257.282");
}

</style>
