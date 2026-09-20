<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na6x-9bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-4" /></template>
<style>
.na6x-9bcj {
  fill: currentColor;
  d: path("M7.385 16.616h1V4h-1zM6.23 21q-.93 0-1.58-.65Q4 19.698 4 18.77V5.23q0-.929.65-1.58Q5.302 3 6.23 3h10.386v14.616H6.23q-.502 0-.866.341Q5 18.3 5 18.804t.365.85t.866.346H19V5h1v16z");
}

</style>
