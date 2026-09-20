<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnb7crbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-dual-4-bar-sharp" /></template>
<style>
.fnb7crbqy {
  fill: currentColor;
  d: path("M1.5 14V9.5h3V14zm6 0V8h3v6zm6 0V6h3v8zm6 0V4h3v10zm-18 6v-4h3v4zm6 0v-4h3v4zm6 0v-4h3v4zm6 0v-4h3v4z");
}

</style>
