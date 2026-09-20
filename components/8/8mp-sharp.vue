<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shxl4jbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:8mp-sharp" /></template>
<style>
.shxl4jbcy {
  fill: currentColor;
  d: path("M10 11.5h4.5v-6H10zM11.5 8V6.5H13V8zm0 2.5V9H13v1.5zm-5.5 8h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm7.5 0H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18z");
}

</style>
