<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpm2yxbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-table-outline-sharp" /></template>
<style>
.lpm2yxbyb {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 8.998h14V5H5zm0 5.004h14V9.998H5zM5 19h14v-3.998H5zM6.77 7.804V6.188h1.615v1.616zm0 5.004v-1.616h1.615v1.616zm0 5.003v-1.615h1.615v1.615z");
}

</style>
