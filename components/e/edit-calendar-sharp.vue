<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9cp53yyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-calendar-sharp" /></template>
<style>
.m9cp53yyg {
  fill: currentColor;
  d: path("M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v6.616h-1v-1H5V20h6.846v1zm10.23 0v-2.21l5.96-5.934l2.19 2.204L16.44 21zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
