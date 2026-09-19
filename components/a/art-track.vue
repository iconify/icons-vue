<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsbpsxbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:art-track" /></template>
<style>
.jsbpsxbmo {
  fill: currentColor;
  d: path("M22 13h-8v-2h8zm0-6h-8v2h8zm-8 10h8v-2h-8zm-2-8v6c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V9c0-1.1.9-2 2-2h6c1.1 0 2 .9 2 2m-1.5 6l-2.25-3l-1.75 2.26l-1.25-1.51L3.5 15z");
}

</style>
