<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6pk-dblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-24-filled" /></template>
<style>
.s6pk-dblw {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.645-1.142l-4.29 1.118a.85.85 0 0 1-1.037-1.037l1.117-4.289A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2m4.28 6.97a.75.75 0 0 0-1.06 0l-4.47 4.47l-1.97-1.97a.75.75 0 1 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5-5a.75.75 0 0 0 0-1.06");
}

</style>
