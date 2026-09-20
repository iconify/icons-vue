<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm-9o_b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kitchen-sharp" /></template>
<style>
.zm-9o_b9j {
  fill: currentColor;
  d: path("M8.192 8h1V5.385h-1zm0 8.116h1v-4.347h-1zM5 21V10.385h14V21zM5 9.385V3h14v6.385z");
}

</style>
