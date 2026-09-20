<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkz3ir86s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-code-sharp" /></template>
<style>
.lkz3ir86s {
  fill: currentColor;
  d: path("M15.35 21.389L12.462 18.5l2.888-2.888l.688.713l-2.175 2.175l2.175 2.175zm3.762 0l-.689-.714l2.175-2.175l-2.175-2.175l.689-.713L22 18.5zM3 19V5h6.596l2 2H21v6.135h-5.558q-2.23 0-3.798 1.538t-1.567 3.558V19z");
}

</style>
