<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwhdhqugn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-vertical-top-outline-sharp" /></template>
<style>
.xwhdhqugn {
  fill: currentColor;
  d: path("M7 22V6h3v16zm7-6V6h3v10zM2 4V2h20v2z");
}

</style>
