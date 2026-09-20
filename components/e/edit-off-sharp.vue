<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4m6xz9cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-off-sharp" /></template>
<style>
.o4m6xz9cx {
  fill: currentColor;
  d: path("M14.685 11.829L12.17 9.315l5.723-5.742l2.527 2.544zm5.077 9.348l-7.21-7.185L6.519 20H4v-2.513l6.014-6.033l-7.191-7.215l.714-.714l16.938 16.938zM17.504 7.589L19 6.111L17.889 5l-1.477 1.496z");
}

</style>
