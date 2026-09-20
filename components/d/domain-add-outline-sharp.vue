<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkaputb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-add-outline-sharp" /></template>
<style>
.vkaputb7f {
  fill: currentColor;
  d: path("M2.73 20.154v-17h9v4h9.54v8.308h-1V8.154h-8.54v3h2.386v1H11.73v3h2.385v1H11.73v3h4.77v1zm1-1h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 12h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm12.54 15v-2h-2v-1h2v-2h1v2h2v1h-2v2zm-3.77-10v-1h1v1zm0 4v-1h1v1z");
}

</style>
