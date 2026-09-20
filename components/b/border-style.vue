<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwzsut_jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-style" /></template>
<style>
.hwzsut_jw {
  fill: currentColor;
  d: path("M7.692 20v-1.23h1.231V20zm3.693 0v-1.23h1.23V20zm3.692 0v-1.23h1.23V20zm3.692 0v-1.23H20V20zm0-3.692v-1.231H20v1.23zm0-3.693v-1.23H20v1.23zm0-3.692v-1.23H20v1.23zM4 20V4h16v1H5v15z");
}

</style>
