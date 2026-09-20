<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t44_e6b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-scanner-sharp" /></template>
<style>
.t44_e6b-g {
  fill: currentColor;
  d: path("M2.5 5.5v-4h4v1h-3v3zm18 0v-3h-3v-1h4v4zm-18 17v-4h1v3h3v1zm15 0v-1h3v-3h1v4zm-12-3v-15h13v15zm4-10h5v-1h-5zm0 3h5v-1h-5zm0 3h5v-1h-5z");
}

</style>
