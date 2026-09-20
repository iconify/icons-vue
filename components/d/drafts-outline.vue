<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdy832vku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drafts-outline" /></template>
<style>
.jdy832vku {
  fill: currentColor;
  d: path("m12 1l9.05 5.4q.45.275.7.75t.25 1V19q0 .825-.587 1.413T20 21H4q-.825 0-1.412-.587T2 19V8.15q0-.525.25-1t.7-.75zm0 11.65L19.8 8L12 3.35L4.2 8zM12 15l-8-4.8V19h16v-8.8zm0 4h8H4z");
}

</style>
