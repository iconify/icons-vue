<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2831b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:border-outer-fill-sharp" /></template>
<style>
.l-2831b6q {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M12.01 6H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m-5 5H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
