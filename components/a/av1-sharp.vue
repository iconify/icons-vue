<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7h9d7bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:av1-sharp" /></template>
<style>
.h7h9d7bdg {
  fill: currentColor;
  d: path("M4.5 15H6v-1.5h1.5V15H9V9H4.5zM6 12v-1.5h1.5V12zm5.75 3h1.5L15 9h-1.5l-1 3.425L11.5 9H10zM18 15h1.5V9h-3v1.5H18zM1 20V4h22v16z");
}

</style>
