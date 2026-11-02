<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_yl2vgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-fill" /></template>
<style>
.fz_yl2vgp {
  fill: currentColor;
  d: path("M7 2h10a3 3 0 0 1 3 3v4H4V5a3 3 0 0 1 3-3m9 4a1 1 0 0 0-2 0v1a1 1 0 0 0 2 0Zm4 5v8a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-8Zm-4 6v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0");
}

</style>
