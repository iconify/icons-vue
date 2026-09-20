<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc9pel1aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-sharp" /></template>
<style>
.yc9pel1aw {
  fill: currentColor;
  d: path("M3 18V6h18v12zm5.23-2.23h7.54v-1.54H8.23zm-3-3h1.54v-1.54H5.23zm3 0h1.54v-1.54H8.23zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zm-12-3h1.54V8.23H5.23zm3 0h1.54V8.23H8.23zm3 0h1.54V8.23h-1.54zm3 0h1.54V8.23h-1.54zm3 0h1.54V8.23h-1.54z");
}

</style>
