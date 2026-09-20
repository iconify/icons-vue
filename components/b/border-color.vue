<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8lzacc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-color" /></template>
<style>
.t8lzacc0y {
  fill: currentColor;
  d: path("M2 24v-2h20v2zm3-6.173v-2.5L16.22 4.113q.159-.16.348-.232t.378-.073q.208 0 .39.073t.349.238l1.029 1.035q.165.16.235.342t.07.39q0 .183-.07.373q-.07.189-.236.354L7.5 17.827zM16.58 7.319l1.44-1.438l-1.074-1.073l-1.438 1.438z");
}

</style>
