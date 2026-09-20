<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzprtrnmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-add-outline-sharp" /></template>
<style>
.tzprtrnmn {
  fill: currentColor;
  d: path("M13 14h2v-3h3V9h-3V6h-2v3h-3v2h3zm-7 4V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
