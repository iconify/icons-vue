<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlk4w4c1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait-sharp" /></template>
<style>
.zlk4w4c1a {
  fill: currentColor;
  d: path("M15 22v-7h5v7ZM4 22V2h16v11h-7v9Z");
}

</style>
