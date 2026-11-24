<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa7dmnp7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-corner-fill" /></template>
<style>
.sa7dmnp7h {
  fill: currentColor;
  d: path("M21 10H11a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1m-5 3a1 1 0 0 1 2 0c0 1.452 1.548 3 3 3a1 1 0 0 1 0 2c-.774 0-1.508.422-2.043.957a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 13 18a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3");
}

</style>
