<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef5izebjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:graphic-eq-off" /></template>
<style>
.ef5izebjs {
  fill: currentColor;
  d: path("M19.775 22.625L13 15.85V22h-2v-8.15l-2-2V18H7V9.85L1.375 4.225L2.8 2.8l18.4 18.4zM3 14v-4h2v4zm10-3.85l-2-2V2h2zm4 4l-2-2V6h2zm2-.15v-4h2v4z");
}

</style>
