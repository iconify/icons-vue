<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnf8i_bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-copy-outline-sharp" /></template>
<style>
.gnf8i_bip {
  fill: currentColor;
  d: path("M7.5 17V3h11v14zm1-1h9V4h-9zm-4 4V6.616h1V19h9.385v1zm4-4V4z");
}

</style>
