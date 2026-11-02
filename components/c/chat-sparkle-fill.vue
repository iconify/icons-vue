<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcwjwmbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-fill" /></template>
<style>
.kcwjwmbgi {
  fill: currentColor;
  d: path("M19 2a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3Zm-7 3a1 1 0 0 0-1 1c0 .363-.097.718-.25 1.046a3.5 3.5 0 0 1-.707.997a3.5 3.5 0 0 1-.997.707C8.718 8.903 8.363 9 8 9a1 1 0 0 0 0 2c.363 0 .718.097 1.046.25c.371.175.709.415.997.707c.292.288.532.626.707.997c.153.328.25.683.25 1.046a1 1 0 0 0 2 0c0-.363.097-.718.25-1.046c.175-.371.415-.709.707-.997c.288-.292.626-.532.997-.707c.328-.153.683-.25 1.046-.25a1 1 0 0 0 0-2c-.363 0-.718-.097-1.046-.25a3.5 3.5 0 0 1-.997-.707a3.5 3.5 0 0 1-.707-.997A2.5 2.5 0 0 1 13 6a1 1 0 0 0-1-1");
}

</style>
