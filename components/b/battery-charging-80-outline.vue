<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2dj_2bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-80-outline" /></template>
<style>
.h2dj_2bks {
  fill: currentColor;
  d: path("M8.692 21q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v6.903q-2.135.275-3.587 1.897t-1.452 3.853q0 .843.227 1.618t.663 1.44zm.192-10.77h6.232V5.463H8.885zm7.693 11.25v-2.634h-1.539l2.385-4.327v2.635h1.539z");
}

</style>
