<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7lmgrhuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-none-sharp" /></template>
<style>
.n7lmgrhuc {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
