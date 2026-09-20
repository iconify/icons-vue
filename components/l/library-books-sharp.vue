<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_4hfsnbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-books-sharp" /></template>
<style>
.l_4hfsnbq {
  fill: currentColor;
  d: path("M10 14h4v-2h-4zm0-3h8V9h-8zm0-3h8V6h-8zM6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
