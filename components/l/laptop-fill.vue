<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k95bcub3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-fill" /></template>
<style>
.k95bcub3x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 15V6C3 4.3431 4.3431 3 6 3H18C19.6569 3 21 4.3431 21 6V15H21.5C22.3284 15 23 15.6716 23 16.5V18C23 19.6569 21.6569 21 20 21H4C2.3431 21 1 19.6569 1 18V16.5C1 15.6716 1.6716 15 2.5 15H3ZM3 17L3 18C3 18.5523 3.4477 19 4 19L20 19C20.5523 19 21 18.5523 21 18L21 17L3 17Z");
}

</style>
