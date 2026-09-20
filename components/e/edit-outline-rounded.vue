<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh2rr-7uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-outline-rounded" /></template>
<style>
.eh2rr-7uz {
  fill: currentColor;
  d: path("M5 19h1.098L16.796 8.302l-1.098-1.098L5 17.902zm-.192 1q-.343 0-.576-.232T4 19.192v-1.04q0-.332.13-.632t.349-.518L17.18 4.287q.153-.137.339-.212T17.907 4t.39.064t.35.228l1.067 1.074q.165.159.226.35q.06.19.06.38q0 .204-.068.39q-.069.185-.218.339L6.998 19.521q-.217.218-.518.348T5.848 20zM19.019 6.092l-1.111-1.111zm-2.781 1.67l-.54-.558l1.098 1.098z");
}

</style>
