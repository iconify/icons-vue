<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkx0ghbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-fill" /></template>
<style>
.nkx0ghbff {
  fill: currentColor;
  d: path("M20.293 2.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414-1.414ZM17 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-1.293 3.293l2 2a2.414 2.414 0 0 1 0 3.414L16.414 15L9 7.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0ZM21 7a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2ZM7.586 9L15 16.414l-.293.293A1 1 0 0 1 14 17h-2.586l-3.707 3.707a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414L7 12.586V10c0-.265.105-.52.293-.707Z");
}

</style>
