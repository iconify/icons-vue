<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z2f9o-5ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-treemap-20-filled" /></template>
<style>
.z2f9o-5ai {
  fill: currentColor;
  d: path("M7 3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h1zm1 14h6a3 3 0 0 0 3-3v-1H8zm9-5V6a3 3 0 0 0-3-3H8v9z");
}

</style>
