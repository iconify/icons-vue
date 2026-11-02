<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df-1vdbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-fill" /></template>
<style>
.df-1vdbwr {
  fill: currentColor;
  d: path("M9 2h3c.265 0 .52.105.707.293L14.414 4H19a3 3 0 0 1 3 3v8a1 1 0 0 1-2 0V7a1 1 0 0 0-1-1h-5a1 1 0 0 1-.707-.293L11.586 4H9a1 1 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3m1.414 8H15a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h3c.265 0 .52.105.707.293Z");
}

</style>
