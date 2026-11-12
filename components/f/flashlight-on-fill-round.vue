<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyke2qb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-fill-round" /></template>
<style>
.kyke2qb2f {
  fill: currentColor;
  d: path("M20.293 2.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414-1.414ZM17 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-1.293 3.293l2 2a2.414 2.414 0 0 1 0 3.414L16.414 15L9 7.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0ZM21 7a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-6.707 8.707l.642.642c-.571.385-1.239.651-1.935.651h-1c-.468 0-.98.395-1.293.707l-3 3a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414l3-3C6.605 12.98 7 12.468 7 12v-1c0-.696.266-1.364.651-1.935Z");
}

</style>
