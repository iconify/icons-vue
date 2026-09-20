<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu17hnbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-distribute-sharp" /></template>
<style>
.pu17hnbac {
  fill: currentColor;
  d: path("M3 21V3h1.23v18zm8-4.5v-9h2v9zm8.77 4.5V3H21v18z");
}

</style>
