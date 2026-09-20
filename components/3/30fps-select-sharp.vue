<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofcnrsbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:30fps-select-sharp" /></template>
<style>
.ofcnrsbhu {
  fill: currentColor;
  d: path("M5.154 13v-1h4.462V9.5H5.154v-1h4.462V6H5.154V5h5.462v8zm8.23 0V5h5.462v8zm1-1h3.462V6h-3.461zM3.847 21.5v-4h1v4zm3.385 0v-4h1v4zm3.384 0v-4h1v4zm3.385 0v-4h6.154v4z");
}

</style>
