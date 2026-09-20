<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njsng5bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-error-outline" /></template>
<style>
.njsng5bmo {
  fill: currentColor;
  d: path("M8.692 21q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v7.45q-.281.092-.522.214q-.24.122-.478.274V5.462H8.885V20h3.738q.068.28.18.521q.113.24.245.479zm7.42 0l-.689-.688l2.1-2.1l-2.1-2.1l.689-.689l2.1 2.1l2.1-2.1l.688.689l-2.075 2.1l2.075 2.1l-.688.688l-2.1-2.075z");
}

</style>
