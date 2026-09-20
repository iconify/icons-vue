<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcor9u8nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-goldenratio-sharp" /></template>
<style>
.gcor9u8nx {
  fill: currentColor;
  d: path("M10 21v-7H3v-1h7v-2H3v-1h7V3h1v7h2V3h1v7h7v1h-7v2h7v1h-7v7h-1v-7h-2v7zm1-8h2v-2h-2z");
}

</style>
