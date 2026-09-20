<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvdqy-b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:copy-all-sharp" /></template>
<style>
.dvdqy-b7v {
  fill: currentColor;
  d: path("M4 17.423v-1.23h1.23v1.23zm0-3.577v-1.23h1.23v1.23zm0-3.577V9.04h1.23v1.23zM7.577 21v-1.23h1.23V21zm.115-3.692V3H19v14.308zM11.154 21v-1.23h1.23V21zM4 21v-1.23h1.23V21zm10.73 0v-1.23h1.232V21zM4 6.692v-1.23h1.23v1.23z");
}

</style>
