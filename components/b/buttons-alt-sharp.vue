<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oayo3wp4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:buttons-alt-sharp" /></template>
<style>
.oayo3wp4s {
  fill: currentColor;
  d: path("M2 18V6h20v12zm5.25-3h1.5v-2.25H11v-1.5H8.75V9h-1.5v2.25H5v1.5h2.25z");
}

</style>
