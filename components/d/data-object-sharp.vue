<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uas45s55s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-object-sharp" /></template>
<style>
.uas45s55s {
  fill: currentColor;
  d: path("M14.52 19v-1H18v-5.771h1.827v-.458H18V5.995h-3.48V5H19v5.927h2v2.146h-2V19zM5 19v-5.927H3v-2.146h2V5h4.48v1H6v5.771H4.173v.458H6v5.776h3.48V19z");
}

</style>
