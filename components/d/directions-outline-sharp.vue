<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8citk7vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-outline-sharp" /></template>
<style>
.y8citk7vw {
  fill: currentColor;
  d: path("M8.5 14.5h1v-3H14v1.789L16.288 11L14 8.692V10.5H8.5zm3.5 6.877L2.623 12L12 2.623L21.377 12zM12 20l8-8l-8-8l-8 8zm0-8");
}

</style>
