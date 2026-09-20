<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg625ob2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:imagesmode-sharp" /></template>
<style>
.pg625ob2u {
  fill: currentColor;
  d: path("M7.5 16.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM4 20V4h16v16zM9.207 9.209q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291");
}

</style>
