<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="extt5ccqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:h-plus-mobiledata-badge-outline-sharp" /></template>
<style>
.extt5ccqr {
  fill: currentColor;
  d: path("M4.5 17h2v-4h4v4h2V7h-2v4h-4V7h-2zm11-2h2v-2h2v-2h-2V9h-2v2h-2v2h2zM1 21V3h22v18zm2-2h18V5H3zm0 0V5z");
}

</style>
