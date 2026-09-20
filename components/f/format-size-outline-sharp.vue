<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptxucpbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-size-outline-sharp" /></template>
<style>
.ptxucpbsa {
  fill: currentColor;
  d: path("M14 20V7H9V4h13v3h-5v13zm-9 0v-8H2V9h9v3H8v8z");
}

</style>
