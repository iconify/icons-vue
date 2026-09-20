<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2cv9vbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-page" /></template>
<style>
.e2cv9vbab {
  fill: currentColor;
  d: path("M4 20V4h1.23v16zm14.77 0V4H20v16zM7.691 12.616v-1.231h1.231v1.23zM11.385 20v-1.23h1.23V20zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zm0-3.692V4h1.23v1.23zm3.692 7.384v-1.23h1.23v1.23z");
}

</style>
