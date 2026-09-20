<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3753fb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-roll-sharp" /></template>
<style>
.a3753fb2t {
  fill: currentColor;
  d: path("M3 21V4h3V2h4v2h3v2h8v13h-8.038v2zm6.423-4.192h1.539v-1.539H9.423zm0-7.077h1.539V8.192H9.423zm3.923 7.077h1.539v-1.539h-1.539zm0-7.077h1.539V8.192h-1.539zm3.923 7.077h1.539v-1.539h-1.539zm0-7.077h1.539V8.192h-1.539z");
}

</style>
