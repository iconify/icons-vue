<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so-tf9xcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fort-sharp" /></template>
<style>
.so-tf9xcs {
  fill: currentColor;
  d: path("M1.5 20.5v-3.288l2-2V8.789l-2-2V3.5h1v2h3v-2h1v2h3v-2h1v3.289l-2 2V10.5h7V8.789l-2-2V3.5h1v2h3v-2h1v2h3v-2h1v3.289l-2 2v6.423l2 2V20.5h-8v-5h-5v5z");
}

</style>
