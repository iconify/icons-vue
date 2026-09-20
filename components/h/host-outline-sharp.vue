<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po98huw9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:host-outline-sharp" /></template>
<style>
.po98huw9o {
  fill: currentColor;
  d: path("M3 20V4h7.808v16zm10.192 0V4H21v16zM4 19h5.808V5H4zm10.192 0H20V5h-5.808zm-8.808-4.615h3v-1h-3zm10.232 0h3v-1h-3zM5.385 11.577h3v-1h-3zm10.23 0h3v-1h-3zM5.386 8.75h3v-1h-3zm10.23 0h3v-1h-3zM4 19h5.808zm10.192 0H20z");
}

</style>
