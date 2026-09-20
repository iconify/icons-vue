<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w73jsacqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-off-sharp" /></template>
<style>
.w73jsacqt {
  fill: currentColor;
  d: path("M21 18.175L7.85 5h1.427l2 2H21zm-.198 4.048L17.579 19H3V5h2l1.616 1.616H5.2L2.546 3.962l.708-.708l18.262 18.262z");
}

</style>
