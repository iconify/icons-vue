<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1tqpuu5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-flex-end-outline-sharp" /></template>
<style>
.g1tqpuu5q {
  fill: currentColor;
  d: path("M20 21V3h1v18zm-5.5-4.5v-9h2v9zm-6 0v-9h2v9z");
}

</style>
