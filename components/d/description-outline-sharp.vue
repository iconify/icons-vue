<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icijg0byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:description-outline-sharp" /></template>
<style>
.icijg0byg {
  fill: currentColor;
  d: path("M8 18h8v-2H8zm0-4h8v-2H8zm-4 8V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
