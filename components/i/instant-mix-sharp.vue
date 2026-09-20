<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvalyqwag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:instant-mix-sharp" /></template>
<style>
.tvalyqwag {
  fill: currentColor;
  d: path("M5.346 19.5v-7.115h-2v-1h5v1h-2V19.5zm0-10.885V4.5h1v4.116zm4.154 0v-1h2V4.5h1v3.116h2v1zm2 10.885v-8.115h1V19.5zm6.154 0v-3.116h-2v-1h5v1h-2V19.5zm0-6.884V4.5h1v8.116z");
}

</style>
