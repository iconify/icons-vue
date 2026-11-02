<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzgr1ybcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-sparkle-fill-sharp" /></template>
<style>
.uzgr1ybcm {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 1 2 0c0 1.452 1.548 3 3 3a1 1 0 0 1 0 2c-.774 0-1.508.422-2.043.957a3.5 3.5 0 0 0-.707.997C8.097 10.282 8 10.637 8 11a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 3 8a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3m15.316 11.051a1 1 0 0 1 0 1.898l-1.465.488l.856.856a1 1 0 0 1 0 1.414l-2 2a1 1 0 0 1-1.414 0l-.856-.856l-.488 1.465a1 1 0 0 1-1.898 0l-3-9a1.001 1.001 0 0 1 1.265-1.265Z");
}

</style>
