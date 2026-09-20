<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zx30qobaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:eject-bold" /></template>
<style>
.zx30qobaq {
  fill: currentColor;
  d: path("M208 152H48a20 20 0 0 0-20 20v20a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20v-20a20 20 0 0 0-20-20m-4 36H52v-12h152ZM48.27 136h159.46a20.27 20.27 0 0 0 14.61-34.3l-73.76-76.92a28.51 28.51 0 0 0-41.16 0L33.66 101.7A20.27 20.27 0 0 0 48.27 136m76.48-94.61a4.49 4.49 0 0 1 6.5 0L199 112H57Z");
}

</style>
