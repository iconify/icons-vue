<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql0f1jbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-share-sharp" /></template>
<style>
.ql0f1jbxt {
  fill: currentColor;
  d: path("M10.654 16.5v-4h6.329l-2.075-2.1l.708-.688L18.904 13l-3.288 3.288l-.714-.713l2.1-2.075h-5.348v3zM7.884 21V4.48h2.424V3h3.384v1.48h2.424v3.462h-1v-2.48H8.885V20h6.23v-1.942h1V21z");
}

</style>
