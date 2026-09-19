<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnumfnbbo"/><path class="vfica3t-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-cellular-2-bar" /></template>
<style>
.mnumfnbbo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M2 22h20V2z");
}

.vfica3t-a {
  fill: currentColor;
  d: path("M14 10L2 22h12z");
}

</style>
