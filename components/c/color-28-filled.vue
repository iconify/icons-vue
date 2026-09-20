<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jo47jnbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-28-filled" /></template>
<style>
.jo47jnbbk {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12c0 4.768-2.782 8.886-6.807 10.821c-3.286 1.58-6.99-.774-7.356-4.299a19 19 0 0 1-.087-2.002c0-.588.004-1.028-.04-1.41c-.042-.365-.122-.614-.255-.813c-.131-.197-.356-.41-.79-.626c-.915-.458-1.67-.112-2.839.406c-.54.24-1.189.517-1.89.584c-.744.071-1.51-.095-2.287-.648c-1.33-.948-1.721-2.639-1.473-4.073C3.153 6.294 8.074 2 14 2m3 16.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m3.5-3.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m1-4.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-3-4a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-5-1.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
