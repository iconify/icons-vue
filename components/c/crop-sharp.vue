<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dggag-y5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-sharp" /></template>
<style>
.dggag-y5q {
  fill: currentColor;
  d: path("M17.5 22.5v-4h-12v-12h-4v-1h4v-4h1v16h16v1h-4v4zm0-6v-10h-10v-1h11v11z");
}

</style>
