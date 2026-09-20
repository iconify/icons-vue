<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5_675bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-left-sharp" /></template>
<style>
.x5_675bso {
  fill: currentColor;
  d: path("M4 16.25v-8.5h8.5v8.5zM4 5V4h16v1zm10.885 3.75v-1H20v1zm0 3.75v-1H20v1zm0 3.75v-1H20v1zM4 20v-1h16v1z");
}

</style>
