<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy018sb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-grid-off" /></template>
<style>
.iy018sb5s {
  fill: currentColor;
  d: path("M8 4v1.45l2 2V4h4v4h-3.45l2 2H14v1.45l2 2V10h4v4h-3.45l2 2H20v1.45l2 2V4c0-1.1-.9-2-2-2H4.55l2 2zm8 0h4v4h-4zM1.27 1.27L0 2.55l2 2V20c0 1.1.9 2 2 2h15.46l2 2l1.27-1.27zM10 12.55L11.45 14H10zm-6-6L5.45 8H4zM8 20H4v-4h4zm0-6H4v-4h3.45l.55.55zm6 6h-4v-4h3.45l.55.54zm2 0v-1.46L17.46 20z");
}

</style>
