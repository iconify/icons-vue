<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ov-wf5bce"/><path class="ejd_d6b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mark-unread-chat-alt" /></template>
<style>
.ejd_d6b8u {
  fill: currentColor;
  d: path("M6 8V6h9.03a4.9 4.9 0 0 1-.92-4H4.01a2 2 0 0 0-2 2L2 22l4-4h14c1.1 0 2-.9 2-2V6.97C21.16 7.61 20.13 8 19 8zm8 6H6v-2h8zm4-3H6V9h12z");
}

.ov-wf5bce {
  cx: 19px;
  cy: 3px;
  r: 3px;
  fill: currentColor;
}

</style>
