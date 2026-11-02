<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7v-a8bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-sparkle-fill" /></template>
<style>
.o7v-a8bdm {
  fill: currentColor;
  d: path("m6.586 6l1.707-1.707C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6H19a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3ZM12 7a1 1 0 0 0-1 1c0 .363-.097.718-.25 1.046a3.5 3.5 0 0 1-.707.997a3.5 3.5 0 0 1-.997.707c-.328.153-.683.25-1.046.25a1 1 0 0 0 0 2c.363 0 .718.097 1.046.25c.371.175.709.415.997.707c.292.288.532.626.707.997c.153.328.25.683.25 1.046a1 1 0 0 0 2 0c0-.363.097-.718.25-1.046c.175-.371.415-.709.707-.997c.288-.292.626-.532.997-.707c.328-.153.683-.25 1.046-.25a1 1 0 0 0 0-2c-.363 0-.718-.097-1.046-.25a3.5 3.5 0 0 1-.997-.707a3.5 3.5 0 0 1-.707-.997A2.5 2.5 0 0 1 13 8a1 1 0 0 0-1-1");
}

</style>
