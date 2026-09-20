<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv0yf6bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-sharp" /></template>
<style>
.zv0yf6bqv {
  fill: currentColor;
  d: path("M3 21v-4.25L17.625 2.175L21.8 6.45L7.25 21zM17.6 7.8L19 6.4L17.6 5l-1.4 1.4z");
}

</style>
