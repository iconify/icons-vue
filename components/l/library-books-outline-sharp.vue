<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdl_8rboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-books-outline-sharp" /></template>
<style>
.sdl_8rboa {
  fill: currentColor;
  d: path("M10 14h4v-2h-4zm0-3h8V9h-8zm0-3h8V6h-8zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
