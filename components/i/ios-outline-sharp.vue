<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te6x-mb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ios-outline-sharp" /></template>
<style>
.te6x-mb8p {
  fill: currentColor;
  d: path("M4.442 8.73V7.5h1.231v1.23zm.116 7.77v-5.77h1v5.77zm3 0v-9h5v9zm1-1h3v-7h-3zm6 1v-1h4v-3h-4v-5h5v1h-4v3h4v5z");
}

</style>
