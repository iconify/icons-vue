<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f27wh-b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-fill" /></template>
<style>
.f27wh-b4b {
  fill: currentColor;
  d: path("M21 21H3a1 1 0 0 1 0-2h1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v2.733l.003-.001a3 3 0 0 1 2.871.487l3 2.4A3 3 0 0 1 20 13.961V19h1a1 1 0 0 1 0 2m-8-9.919V19h5v-5.039a1 1 0 0 0-.375-.781l-3-2.4a1 1 0 0 0-1.25 0Z");
}

</style>
