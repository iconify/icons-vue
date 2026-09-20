<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktop44b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-3-2-sharp" /></template>
<style>
.ktop44b7y {
  fill: currentColor;
  d: path("M3 18V6h18v12z");
}

</style>
