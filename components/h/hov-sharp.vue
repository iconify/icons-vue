<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5qk1gqvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hov-sharp" /></template>
<style>
.c5qk1gqvw {
  fill: currentColor;
  d: path("m12 21l-5-9.02L12 3l5 8.98z");
}

</style>
