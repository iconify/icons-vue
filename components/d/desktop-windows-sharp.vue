<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mud3xccvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-windows-sharp" /></template>
<style>
.mud3xccvm {
  fill: currentColor;
  d: path("M8 21v-2h2v-2H2V3h20v14h-8v2h2v2z");
}

</style>
