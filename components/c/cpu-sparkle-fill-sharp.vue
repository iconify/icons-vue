<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okst-tb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-fill-sharp" /></template>
<style>
.okst-tb8y {
  fill: currentColor;
  d: path("M9 3v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2a1 1 0 0 1 1 1v2h1a1 1 0 0 1 0 2h-1v2h1a1 1 0 0 1 0 2h-1v2h1a1 1 0 0 1 0 2h-1v2a1 1 0 0 1-1 1h-2v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1H9v1a1 1 0 0 1-2 0v-1H5a1 1 0 0 1-1-1v-2H3a1 1 0 0 1 0-2h1v-2H3a1 1 0 0 1 0-2h1V9H3a1 1 0 0 1 0-2h1V5a1 1 0 0 1 1-1h2V3a1 1 0 0 1 2 0m3 4a1 1 0 0 0-1 1c0 .363-.097.718-.25 1.046a3.5 3.5 0 0 1-.707.997a3.5 3.5 0 0 1-.997.707c-.328.153-.683.25-1.046.25a1 1 0 0 0 0 2c.363 0 .718.097 1.046.25c.371.175.709.415.997.707c.292.288.532.626.707.997c.153.328.25.683.25 1.046a1 1 0 0 0 2 0c0-.363.097-.718.25-1.046c.175-.371.415-.709.707-.997c.288-.292.626-.532.997-.707c.328-.153.683-.25 1.046-.25a1 1 0 0 0 0-2c-.363 0-.718-.097-1.046-.25a3.5 3.5 0 0 1-.997-.707a3.5 3.5 0 0 1-.707-.997A2.5 2.5 0 0 1 13 8a1 1 0 0 0-1-1");
}

</style>
