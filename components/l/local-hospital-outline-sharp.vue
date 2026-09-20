<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8i1v460q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-hospital-outline-sharp" /></template>
<style>
.p8i1v460q {
  fill: currentColor;
  d: path("M11.25 16.5h1.5v-3.75h3.75v-1.5h-3.75V7.5h-1.5v3.75H7.5v1.5h3.75zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
