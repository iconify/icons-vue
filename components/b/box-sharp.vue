<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el04tmb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:box-sharp" /></template>
<style>
.el04tmb7m {
  fill: currentColor;
  d: path("M3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25zM8 16l4-2l4 2V8H8z");
}

</style>
