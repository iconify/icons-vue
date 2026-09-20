<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":118};
const content = `<path class="wioachbxl"/><path class="w4v22vbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:alpinejs-icon" /></template>
<style>
.w4v22vbpd {
  fill: var(--svg-color--2d3441, #2d3441);
  d: path("m56.889 0l117.938 117.421H61.049L0 56.639z");
}

.wioachbxl {
  fill: var(--svg-color--77c1d2, #77c1d2);
  d: path("M199.111 0L256 56.639l-56.889 56.64l-56.889-56.64z");
}

</style>
