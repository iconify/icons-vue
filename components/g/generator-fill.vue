<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7dt3j7kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:generator-fill" /></template>
<style>
.a7dt3j7kl {
  fill: currentColor;
  d: path("M4 6.171V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v1.171A3 3 0 0 1 22 9v8a3 3 0 0 1-3 3v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-1a3 3 0 0 1-3-3V9c0-1.27.803-2.405 2-2.829M18 5a1 1 0 0 0-1-1H7a.997.997 0 0 0-1 1v1h12Zm-9.586 7l1.293-1.293a.999.999 0 1 0-1.414-1.414l-3 3A1 1 0 0 0 6 14h1.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3A1 1 0 0 0 10 12ZM17 10h-3a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2m-3 4a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2Z");
}

</style>
