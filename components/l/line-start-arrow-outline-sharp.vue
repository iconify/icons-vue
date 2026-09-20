<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgnj2623o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-arrow-outline-sharp" /></template>
<style>
.vgnj2623o {
  fill: currentColor;
  d: path("M13 19L2 12l11-7v6h9v2h-9zm-2-3.65v-6.7L5.725 12zM11 12");
}

</style>
