<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsax9fah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keep" /></template>
<style>
.aqsax9fah {
  fill: currentColor;
  d: path("m16 12l2 2v2h-5v6l-1 1l-1-1v-6H6v-2l2-2V5H7V3h10v2h-1z");
}

</style>
