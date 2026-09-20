<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n51va-lzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dht" /></template>
<style>
.n51va-lzr {
  fill: var(--svg-color--00a0d0, #00a0d0);
  d: path("m13.564 3.005l-3.129 1.246v14.444l3.13-1.251V3zm-5.736 8.813L4.7 13.079V21l3.128-1.257zM19.3 9.72l-3.129-1.235v9.542L19.3 19.29z");
}

</style>
