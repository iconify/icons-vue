<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q18v9vb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-tab-rtl" /></template>
<style>
.q18v9vb-x {
  fill: currentColor;
  d: path("M4 17.5H3v-11h1zm7.673-.212L6.385 12l5.288-5.288l.688.688l-4.055 4.1H21v1H8.287l4.1 4.1z");
}

</style>
