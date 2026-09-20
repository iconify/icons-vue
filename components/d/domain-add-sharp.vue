<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh9aytgon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:domain-add-sharp" /></template>
<style>
.dh9aytgon {
  fill: currentColor;
  d: path("M2 21V3h10v4h10v8h-2V9h-8v2h2v2h-2v2h2v2h-2v2h4v2zm2-2h2v-2H4zm0-4h2v-2H4zm0-4h2V9H4zm0-4h2V5H4zm4 12h2v-2H8zm0-4h2v-2H8zm0-4h2V9H8zm0-4h2V5H8zm12 16v-2h-2v-2h2v-2h2v2h2v2h-2v2zm-4-10v-2h2v2zm0 4v-2h2v2z");
}

</style>
