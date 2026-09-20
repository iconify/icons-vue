<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rle875bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-5" /></template>
<style>
.rle875bii {
  fill: currentColor;
  d: path("M6.98 21q-.816 0-1.398-.541Q5 19.917 5 19.119V5.766q0-.778.53-1.364t1.306-.748l8.78-1.854v14.616l-8.86 1.919q-.302.069-.529.276q-.227.206-.227.508q0 .39.292.636t.689.245H18V5h1v16zm.405-3.81l1-.207V4.36l-1 .207z");
}

</style>
