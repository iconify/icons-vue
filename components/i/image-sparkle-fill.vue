<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sphbc-3ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-fill" /></template>
<style>
.sphbc-3ss {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-1.676a1 1 0 0 0-.203-.293l-8.414-8.414a2.414 2.414 0 0 0-3.414 0L2 16.586Zm12 0a1 1 0 0 0-1 1c0 .363-.097.718-.25 1.046a3.5 3.5 0 0 1-.707.997a3.5 3.5 0 0 1-.997.707c-.328.153-.683.25-1.046.25a1 1 0 0 0 0 2c.363 0 .718.097 1.046.25c.371.175.709.415.997.707c.292.288.532.626.707.997c.153.328.25.683.25 1.046a1 1 0 0 0 2 0c0-.363.097-.718.25-1.046c.175-.371.415-.709.707-.997c.288-.292.626-.532.997-.707c.328-.153.683-.25 1.046-.25a1 1 0 0 0 0-2c-.363 0-.718-.097-1.046-.25a3.5 3.5 0 0 1-.997-.707a3.5 3.5 0 0 1-.707-.997A2.5 2.5 0 0 1 15 6a1 1 0 0 0-1-1m-1.414 15l2 2H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l4.414-4.414a.414.414 0 0 1 .586 0Z");
}

</style>
