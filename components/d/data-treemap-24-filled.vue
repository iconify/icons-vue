<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruy7jzbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-treemap-24-filled" /></template>
<style>
.ruy7jzbjh {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3H9v18H6.25A3.25 3.25 0 0 1 3 17.75zM10.5 21h7.25A3.25 3.25 0 0 0 21 17.75V15.5H10.5zM21 14V6.25A3.25 3.25 0 0 0 17.75 3H10.5v11z");
}

</style>
