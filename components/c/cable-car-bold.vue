<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lz47ndhts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cable-car-bold" /></template>
<style>
.lz47ndhts {
  fill: currentColor;
  d: path("M251.81 29.89a12 12 0 0 0-13.92-9.7l-224 40A12 12 0 0 0 16 84a12 12 0 0 0 2.12-.19L116 66.33V92H64a36 36 0 0 0-36 36v64a36 36 0 0 0 36 36h128a36 36 0 0 0 36-36v-64a36 36 0 0 0-36-36h-52V62.05l102.11-18.24a12 12 0 0 0 9.7-13.92M108 156v-40h40v40Zm-44-40h20v40H52v-28a12 12 0 0 1 12-12m128 88H64a12 12 0 0 1-12-12v-12h152v12a12 12 0 0 1-12 12m12-76v28h-32v-40h20a12 12 0 0 1 12 12");
}

</style>
