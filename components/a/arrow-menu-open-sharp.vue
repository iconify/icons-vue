<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmww7ihsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-menu-open-sharp" /></template>
<style>
.dmww7ihsb {
  fill: currentColor;
  d: path("M10 20V4h1v16zm3.385-4.365v-7.25L16.865 12z");
}

</style>
