<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8uirzysi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:floor-lamp-sharp" /></template>
<style>
.z8uirzysi {
  fill: currentColor;
  d: path("M11 19v-8H4.65l2.775-9h9.15l2.775 9H13v8zm-3 3v-2h8v2z");
}

</style>
