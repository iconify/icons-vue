<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myd0pk6xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-top-outline" /></template>
<style>
.myd0pk6xz {
  fill: currentColor;
  d: path("M4 20v-1.23h1.23V20zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zM4 5V4h16v1zm3.692 15v-1.23h1.231V20zm0-7.384v-1.231h1.231v1.23zM11.385 20v-1.23h1.23V20zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zM15.077 20v-1.23h1.23V20zm0-7.384v-1.231h1.23v1.23zM18.769 20v-1.23H20V20zm0-3.692v-1.231H20v1.23zm0-3.693v-1.23H20v1.23zm0-3.692v-1.23H20v1.23z");
}

</style>
