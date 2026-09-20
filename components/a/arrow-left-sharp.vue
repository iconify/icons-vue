<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ft3qbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-left-sharp" /></template>
<style>
.o3ft3qbpp {
  fill: currentColor;
  d: path("M13.5 15.808L9.692 12L13.5 8.192z");
}

</style>
