<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8o68hb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-save-off" /></template>
<style>
.j8o68hb4z {
  fill: currentColor;
  d: path("M14.5 23.5v-1h5.887l-8.271-8.271V19.5h-6q-.652 0-1.134-.482T4.5 17.884V6.615L1.412 3.5l.688-.688L21.788 22.5v1zm5.689-5.4l-.689-.713l1.1-1.1l.688.713zM18.5 16.387l-1-1v-1.868h1zm-5.252-5.252L5.05 2.942q.206-.202.479-.322t.587-.12H13L18.5 8v3.135zM12.5 8.5h5l-5-5z");
}

</style>
