<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pic33cbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-90" /></template>
<style>
.pic33cbbl {
  fill: currentColor;
  d: path("M8.692 21q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v6.903q-2.135.275-3.587 1.897t-1.452 3.853q0 .843.227 1.618t.663 1.44zm.192-13.154h6.232V5.461H8.885zm7.693 13.635v-2.635h-1.539l2.385-4.327v2.635h1.539z");
}

</style>
