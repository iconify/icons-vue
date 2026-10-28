<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olc5v8ata"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:input-search-outline-sharp" /></template>
<style>
.olc5v8ata {
  fill: currentColor;
  d: path("M5 18h14zm-2 2V10h6v2H5v6h14v-3h2v5zM14.5 9q1.05 0 1.775-.725T17 6.5t-.725-1.775T14.5 4t-1.775.725T12 6.5t.725 1.775T14.5 9m0 2q-1.875 0-3.188-1.312T10 6.5t1.313-3.187T14.5 2t3.188 1.313T19 6.5q0 .675-.187 1.288T18.3 8.925l3.15 3.125l-1.4 1.4l-3.15-3.125q-.525.325-1.137.5T14.5 11");
}

</style>
