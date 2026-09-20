<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myyiprbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:finance-mode-outline" /></template>
<style>
.myyiprbhb {
  fill: currentColor;
  d: path("M8.692 12.266V6.692h1.616v5.574l-.808-.824zm4.347 2.23V2.692h1.615v10.189zM4.307 16.64v-5.947h1.615v4.331zm-.116 3.911l5.297-5.296l3.55 3.05l6.753-6.754H17.5v-1h4v4h-1v-2.292l-7.438 7.438l-3.55-3.05l-3.904 3.904z");
}

</style>
