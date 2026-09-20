<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8fz6_14x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-windows-outline-sharp" /></template>
<style>
.e8fz6_14x {
  fill: currentColor;
  d: path("M8 21v-2h2v-2H2V3h20v14h-8v2h2v2zm-4-6h16V5H4zm0 0V5z");
}

</style>
