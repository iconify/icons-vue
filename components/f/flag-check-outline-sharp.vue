<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c217tozid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-check-outline-sharp" /></template>
<style>
.c217tozid {
  fill: currentColor;
  d: path("M6 20.5V5h4.98q-.028.25-.045.5q-.018.25.007.5H7v6h7.25l.4 2H18v-2.13q.25-.02.5-.057t.5-.11V15h-5.192l-.4-2H7v7.5zM16.602 7.562l3.34-3.335l-.626-.627l-2.714 2.702L15.3 5l-.627.633zm3.541-4.855q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165");
}

</style>
