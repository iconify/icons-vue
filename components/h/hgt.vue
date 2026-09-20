<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk3w-ybbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hgt" /></template>
<style>
.vk3w-ybbm {
  fill: var(--svg-color--ffc908, #ffc908);
  d: path("M8.062 8.08V3L12 6.703zm0 7.85V21L12 17.296zm0-7.868H3l3.697 4.008zm7.875 0H21l-3.688 3.875zm0 .018V3L12 6.703zm0 7.854V21L12 17.296zm-7.875.003H3l3.715-3.859zm7.875 0H21l-3.71-3.958zM12 14.25a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

</style>
