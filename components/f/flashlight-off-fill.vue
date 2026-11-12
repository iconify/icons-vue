<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb9t-db6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-off-fill" /></template>
<style>
.nb9t-db6w {
  fill: currentColor;
  d: path("M17.707 10.293a2.414 2.414 0 0 1 0 3.414L16.414 15L9 7.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0ZM15 16.414l-.293.293A1 1 0 0 1 14 17h-2.586l-3.707 3.707a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414L7 12.586V10c0-.265.105-.52.293-.707L7.586 9Z");
}

</style>
