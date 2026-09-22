<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4wcp7b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:closed-caption-display-sharp" /></template>
<style>
.y4wcp7b2z {
  fill: currentColor;
  d: path("M11 22v-8h11v8zm2-2h7v-4h-7zM3 20V4h18v8h-6.5v-1.5h2v.5H18V9h-5v3H9v1.5H7.5v-3h2v.5H11V9H6v6h3v5z");
}

</style>
