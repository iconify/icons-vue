<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abe6--brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crossword-sharp" /></template>
<style>
.abe6--brr {
  fill: currentColor;
  d: path("M9 22v-6h6v6zm-7-7V9h6v6zm7 0V9h6v6zm7 0V9h6v6zm0-7V2h6v6z");
}

</style>
