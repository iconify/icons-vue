<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-6nm8ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-save-sharp" /></template>
<style>
.dx-6nm8ky {
  fill: currentColor;
  d: path("M14.5 23.5v-1h7v1zm3.5-3.212L14.712 17l.688-.688l2.1 2.1v-4.887h1v4.887l2.1-2.1l.688.688zM4.5 19.5v-17H13L18.5 8v3.14h-6.384v8.36zm8-11h5l-5-5z");
}

</style>
