<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br2k8ftaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dynamic-form" /></template>
<style>
.br2k8ftaj {
  fill: currentColor;
  d: path("M4.116 11q-.667 0-1.141-.475T2.5 9.385v-3.27q0-.666.475-1.14t1.14-.475H13V11zm0 8.5q-.667 0-1.141-.475t-.475-1.14v-3.27q0-.666.475-1.14T4.115 13H15v6.5zM17 19.5V11h-2V4.5h6.27l-2 5.116h1.96zM5 17h1.5v-1.5H5zm0-8.5h1.5V7H5z");
}

</style>
