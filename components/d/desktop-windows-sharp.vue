<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zedo2abil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-windows-sharp" /></template>
<style>
.zedo2abil {
  fill: currentColor;
  d: path("M9 20v-1h2v-2H3V4h18v13h-8v2h2v1z");
}

</style>
