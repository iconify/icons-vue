<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqr43_b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-scanner-outline-sharp" /></template>
<style>
.cqr43_b6s {
  fill: currentColor;
  d: path("M2.5 5.5v-4h4v1h-3v3zm18 0v-3h-3v-1h4v4zm-18 17v-4h1v3h3v1zm15 0v-1h3v-3h1v4zm-11-4h11v-13h-11zm-1 1v-15h13v15zm4-10h5v-1h-5zm0 3h5v-1h-5zm0 3h5v-1h-5zm-3 2.385V5.5v13z");
}

</style>
