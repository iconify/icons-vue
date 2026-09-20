<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp2m6d14x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:iron-outline-sharp" /></template>
<style>
.bp2m6d14x {
  fill: currentColor;
  d: path("M2 18v-3q0-1.65 1.175-2.825T6 11h9V9H9v1H7V7h10v7h1V6h4v2h-2v8h-3v2zm2-2h11v-3H6q-.825 0-1.412.588T4 15zm11 0v-3z");
}

</style>
