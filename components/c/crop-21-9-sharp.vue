<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cytol_8_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-21-9-sharp" /></template>
<style>
.cytol_8_c {
  fill: currentColor;
  d: path("M3 16V8h18v8z");
}

</style>
