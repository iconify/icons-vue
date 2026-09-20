<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4kz7hbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-chromebook" /></template>
<style>
.g4kz7hbgn {
  fill: currentColor;
  d: path("M1 18.308v-1h2V4.538h18v12.77h2v1zm9-1h4v-.77h-4z");
}

</style>
