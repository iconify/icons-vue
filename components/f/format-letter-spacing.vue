<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9w90acgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-letter-spacing" /></template>
<style>
.v9w90acgf {
  fill: currentColor;
  d: path("m8.5 21.02l-3.308-3.308L8.5 14.423l.714.708l-2.1 2.08h9.753l-2.075-2.08l.708-.708l3.289 3.289l-3.308 3.307l-.714-.707l2.1-2.1H7.114l2.075 2.1zM6 11.5V3h1v8.5zm5.5 0V3h1v8.5zm5.5 0V3h1v8.5z");
}

</style>
