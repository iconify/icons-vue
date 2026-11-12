<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a82a-xbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-off-fill-sharp" /></template>
<style>
.a82a-xbtt {
  fill: currentColor;
  d: path("M18.707 11.293a1 1 0 0 1 0 1.414L16.414 15L9 7.586l2.293-2.293a1 1 0 0 1 1.414 0ZM15 16.414l-.293.293A1 1 0 0 1 14 17h-2.586l-4.707 4.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 0-1.414L7 12.586V10c0-.265.105-.52.293-.707L7.586 9Z");
}

</style>
