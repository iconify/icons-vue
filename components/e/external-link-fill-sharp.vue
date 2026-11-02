<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljt277w5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-fill-sharp" /></template>
<style>
.ljt277w5l {
  fill: currentColor;
  d: path("M21 9a1 1 0 0 1-2 0V6.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L17.586 5H15a1 1 0 0 1 0-2h5a.997.997 0 0 1 1 1ZM10 6H6v12h12v-4a1 1 0 0 1 2 0v5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h5a1 1 0 0 1 0 2");
}

</style>
