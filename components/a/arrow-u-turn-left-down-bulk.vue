<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmoba_wbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-down-bulk" /></template>
<style>
.fmoba_wbh {
  fill: currentColor;
  d: path("m8.293 21.707l-4-4a.999.999 0 1 1 1.414-1.414L8 18.586V5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v8a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-6a.997.997 0 0 0-1 1v13.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
