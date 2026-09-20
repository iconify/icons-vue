<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us3jfsahx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-card-sharp" /></template>
<style>
.us3jfsahx {
  fill: currentColor;
  d: path("M4 11.192h16V8.808H4zM19.5 21.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zM3 19V5h18v7.5h-1.5q-2.075 0-3.537 1.463T14.5 17.5V19z");
}

</style>
