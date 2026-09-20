<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpnw74b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:double-arrow-outline" /></template>
<style>
.cpnw74b8t {
  fill: currentColor;
  d: path("m6.05 19l5-7l-5-7H8.5l5 7l-5 7zM12 19l5-7l-5-7h2.45l5 7l-5 7z");
}

</style>
