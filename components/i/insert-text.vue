<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2qzchbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:insert-text" /></template>
<style>
.h2qzchbgy {
  fill: currentColor;
  d: path("M11 16v-6H8V8h8v2h-3v6zM1 23v-6h2V7H1V1h6v2h10V1h6v6h-2v10h2v6h-6v-2H7v2zm6-4h10v-2h2V7h-2V5H7v2H5v10h2z");
}

</style>
