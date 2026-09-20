<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwh2a7bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-sharp" /></template>
<style>
.jwh2a7bvv {
  fill: currentColor;
  d: path("M8.5 14.5h1v-3H14v1.789L16.288 11L14 8.692V10.5H8.5zm3.5 6.877L2.623 12L12 2.623L21.377 12z");
}

</style>
