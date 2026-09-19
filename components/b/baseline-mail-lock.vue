<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydopmcbbp"/><path class="jp9c1zb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mail-lock" /></template>
<style>
.jp9c1zb_x {
  fill: currentColor;
  d: path("M23 15v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-1 0h-2v-1c0-.55.45-1 1-1s1 .45 1 1z");
}

.ydopmcbbp {
  fill: currentColor;
  d: path("M22 9.97V6c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h12v-5.03c0-2.76 2.24-5 5-5zM20 8l-8 5l-8-5V6l8 5l8-5z");
}

</style>
