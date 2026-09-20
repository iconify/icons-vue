<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gep0zjktx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-code-outline-sharp" /></template>
<style>
.gep0zjktx {
  fill: currentColor;
  d: path("M4 18V6v12.5zm-1 1V5h6.596l2 2H21v6.135h-1V8h-8.806l-2-2H4v12h6.077v1zm12.35 2.389L12.462 18.5l2.888-2.888l.688.713l-2.175 2.175l2.175 2.175zm3.762 0l-.689-.714l2.175-2.175l-2.175-2.175l.689-.713L22 18.5z");
}

</style>
