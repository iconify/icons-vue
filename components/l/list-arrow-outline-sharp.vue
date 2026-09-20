<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_kt0dpav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-arrow-outline-sharp" /></template>
<style>
.t_kt0dpav {
  fill: currentColor;
  d: path("M6.173 18.904L3 15.769l.708-.688l1.965 1.877V5.904h1v11.054l1.985-1.877l.688.688zm6.193-.808v-1H21v1zm0-5.577v-1H21v1zm0-5.577v-1H21v1z");
}

</style>
