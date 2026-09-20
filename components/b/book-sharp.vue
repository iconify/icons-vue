<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s90rsqb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-sharp" /></template>
<style>
.s90rsqb4w {
  fill: currentColor;
  d: path("M5 21V3h14v18zm7-10.885l2-1.192l2 1.192V4h-4z");
}

</style>
