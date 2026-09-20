<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh2t14boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-spanish-sharp" /></template>
<style>
.zh2t14boi {
  fill: currentColor;
  d: path("M13 16.5v-2h1v1h4v-3h-5v-5h6v2h-1v-1h-4v3h5v5zm-8-9h6v1H6v3h4v1H6v3h5v1H5z");
}

</style>
