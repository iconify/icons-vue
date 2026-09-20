<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l02w15boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-5-sharp" /></template>
<style>
.l02w15boz {
  fill: currentColor;
  d: path("M9 17h6v-6h-4V9h4V7H9v6h4v2H9zm-6 4V3h18v18z");
}

</style>
