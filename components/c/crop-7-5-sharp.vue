<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygtvc5brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-7-5-sharp" /></template>
<style>
.ygtvc5brp {
  fill: currentColor;
  d: path("M4 18V6h16v12z");
}

</style>
