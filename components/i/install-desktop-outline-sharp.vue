<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo_au3bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:install-desktop-outline-sharp" /></template>
<style>
.wo_au3bru {
  fill: currentColor;
  d: path("M9 20v-2H3V4h8.923v1H4v12h16v-2.5h1V18h-6v2zm7.846-6.75L12.54 8.942l.688-.688l3.12 3.113V4h1v7.367l3.119-3.113l.688.688z");
}

</style>
