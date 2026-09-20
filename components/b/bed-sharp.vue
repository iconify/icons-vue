<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzk56xbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bed-sharp" /></template>
<style>
.fzk56xbgt {
  fill: currentColor;
  d: path("M3 18v-7h1V7h16v4h1v7h-1v-2H4v2zm9.5-7H19V8h-6.5zM5 11h6.5V8H5z");
}

</style>
