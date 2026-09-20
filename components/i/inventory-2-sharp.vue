<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-oku9bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:inventory-2-sharp" /></template>
<style>
.c-oku9bdc {
  fill: currentColor;
  d: path("M3 22V9H2V2h20v7h-1v13zM4 7h16V4H4zm5 7h6v-2H9z");
}

</style>
