<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6u6youio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-page-width-sharp" /></template>
<style>
.c6u6youio {
  fill: currentColor;
  d: path("M9 15V9l-3 3zm9-3l-3-3v6zM2 20V4h20v16z");
}

</style>
