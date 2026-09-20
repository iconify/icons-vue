<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr62x5iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:go-to-line-outline-sharp" /></template>
<style>
.zr62x5iew {
  fill: currentColor;
  d: path("M10.5 7V4h3v3zm0 13v-3h3v3z");
}

</style>
