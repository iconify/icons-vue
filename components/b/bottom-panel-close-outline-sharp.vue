<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sprwmjbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-panel-close-outline-sharp" /></template>
<style>
.sprwmjbgk {
  fill: currentColor;
  d: path("m12 11.596l3.173-3.192H8.827zM5 19h14v-3H5zm0-4h14V5H5zm0 1v3zm-1 4V4h16v16z");
}

</style>
