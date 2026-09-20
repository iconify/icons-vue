<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yicufynlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-6-sharp" /></template>
<style>
.yicufynlv {
  fill: currentColor;
  d: path("M10.5 11.5v-3h3v-1h-4v9h5v-5zm0 1h3v3h-3zM4 20V4h16v16z");
}

</style>
