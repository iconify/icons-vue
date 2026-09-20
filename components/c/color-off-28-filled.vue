<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xnrsvibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-off-28-filled" /></template>
<style>
.xnrsvibtw {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06l-2.785-2.785a12 12 0 0 1-2.742 1.826c-3.287 1.58-6.99-.774-7.356-4.299a19 19 0 0 1-.087-2.002c0-.588.003-1.028-.04-1.41c-.042-.365-.122-.614-.255-.813c-.132-.197-.356-.41-.79-.626c-.915-.458-1.67-.112-2.839.406c-.54.24-1.189.517-1.89.584c-.744.071-1.51-.095-2.287-.648c-1.33-.948-1.721-2.639-1.473-4.073a11.96 11.96 0 0 1 2.826-5.877L2.22 3.28a.75.75 0 0 1 0-1.06M17 18.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M14 2c6.627 0 12 5.373 12 12c0 2.5-.766 4.821-2.074 6.743l-2.857-2.856a1.5 1.5 0 1 0-1.958-1.958L7.257 4.074A11.94 11.94 0 0 1 14 2m7.5 8.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-3-4a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-5-1.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
