<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmytzntus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-shape-up-outline-sharp" /></template>
<style>
.nmytzntus {
  fill: currentColor;
  d: path("M8 21v-6H3l9-11l9 11h-5v6zm2-2h4v-6h2.775L12 7.15L7.225 13H10zm2-6");
}

</style>
