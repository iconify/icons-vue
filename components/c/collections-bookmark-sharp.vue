<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln5_fkbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collections-bookmark-sharp" /></template>
<style>
.ln5_fkbyx {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2zM13 4v7l2.5-1.5L18 11V4z");
}

</style>
