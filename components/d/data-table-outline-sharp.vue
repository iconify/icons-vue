<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg69kubll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-table-outline-sharp" /></template>
<style>
.eg69kubll {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 8.325h14V5H5zm0 5.35h14v-3.35H5zM5 19h14v-3.325H5zM6 7.65v-2h2v2zM6 13v-2h2v2zm0 5.35v-2h2v2z");
}

</style>
