<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ttsid9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dehaze-outline-sharp" /></template>
<style>
.v2ttsid9z {
  fill: currentColor;
  d: path("M4 7V6h16v1zm0 11v-1h16v1zm0-5.5v-1h16v1z");
}

</style>
