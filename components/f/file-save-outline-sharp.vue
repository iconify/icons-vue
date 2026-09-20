<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh-65t9jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-save-outline-sharp" /></template>
<style>
.mh-65t9jg {
  fill: currentColor;
  d: path("M18 20.289L21.288 17l-.688-.688l-2.1 2.1v-4.887h-1v4.887l-2.1-2.1l-.688.688zM14.5 23.5v-1h7v1zm-10-4v-17H13L18.5 8v3.14h-1V8.5h-5v-5h-7v15h6.616v1zm1-1v-15z");
}

</style>
