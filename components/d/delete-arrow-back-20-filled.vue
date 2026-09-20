<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sik3gwd9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:delete-arrow-back-20-filled" /></template>
<style>
.sik3gwd9l {
  fill: currentColor;
  d: path("M11.5 4a1.5 1.5 0 0 0-3 0zm-4 0a2.5 2.5 0 0 1 5 0h5a.5.5 0 0 1 0 1h-1.054l-.485 4.196A5.5 5.5 0 0 0 10.257 18H7.728a3 3 0 0 1-2.98-2.656L3.554 5H2.5a.5.5 0 0 1 0-1zm7 15a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m-.896-6.396l-.897.896h1.543A2.75 2.75 0 0 1 17 16.25v.25a.5.5 0 0 1-1 0v-.25a1.75 1.75 0 0 0-1.75-1.75h-1.543l.897.896a.5.5 0 0 1-.708.708l-1.752-1.753a.5.5 0 0 1 .002-.705l1.75-1.75a.5.5 0 0 1 .708.708");
}

</style>
