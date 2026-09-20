<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbfd5q7zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:elevator-sharp" /></template>
<style>
.cbfd5q7zl {
  fill: currentColor;
  d: path("M7 18h3v-4h1V9.5H6V14h1zm2.388-9.862q.362-.363.362-.888t-.363-.888T8.5 6t-.888.363t-.362.887t.363.888t.887.362t.888-.363M13 11h5l-2.5-4zm2.5 6l2.5-4h-5zM3 21V3h18v18z");
}

</style>
