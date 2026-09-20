<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4we5ebue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-free-sharp" /></template>
<style>
.g4we5ebue {
  fill: currentColor;
  d: path("M3 21v-6h2v4h4v2zm12 0v-2h4v-4h2v6zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6z");
}

</style>
