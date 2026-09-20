<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqj7w-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmarks-outline-sharp" /></template>
<style>
.bsqj7w-ln {
  fill: currentColor;
  d: path("M4 22V6h12v16l-6-3zm2-3.025l4-2.15l4 2.15V8H6zM18 18V4H7V2h13v16zM6 8h8z");
}

</style>
