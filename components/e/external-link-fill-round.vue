<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsdozl7jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-fill-round" /></template>
<style>
.hsdozl7jt {
  fill: currentColor;
  d: path("M21 9a1 1 0 0 1-2 0V6.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L17.586 5H15a1 1 0 0 1 0-2h5a.997.997 0 0 1 1 1ZM10 6H9a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3v-1a1 1 0 0 1 2 0v1a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 20H9a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h1a1 1 0 0 1 0 2");
}

</style>
