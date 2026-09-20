<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd57mfbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-full-outline-sharp" /></template>
<style>
.jd57mfbtj {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18z");
}

</style>
