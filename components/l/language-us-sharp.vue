<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyt7_db3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-us-sharp" /></template>
<style>
.nyt7_db3j {
  fill: currentColor;
  d: path("M5 16.5v-9h1v8h3.904v-8h1v9zm8 0v-2h1v1h4v-3h-5v-5h6v2h-1v-1h-4v3h5v5z");
}

</style>
