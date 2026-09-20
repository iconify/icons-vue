<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-u27x01k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-landscape-sharp" /></template>
<style>
.i-u27x01k {
  fill: currentColor;
  d: path("M2 20V4h20v7h-7v9Zm15 0v-7h5v7Z");
}

</style>
