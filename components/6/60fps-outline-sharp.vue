<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifgdf_6fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:60fps-outline-sharp" /></template>
<style>
.ifgdf_6fq {
  fill: currentColor;
  d: path("M2.885 18.116V5.885h6.23v1.23h-5v3.77h6v7.23zm1.23-1.231h4.77v-4.77h-4.77zm10 0h5.77v-9.77h-5.77zm-1.23 1.23V5.886h8.23v12.23z");
}

</style>
