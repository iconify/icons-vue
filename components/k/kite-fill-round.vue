<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da2672bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-fill-round" /></template>
<style>
.da2672bef {
  fill: currentColor;
  d: path("M11 2.465V8H3.488c.522-.728 1.215-1.337 1.957-1.832ZM13 8V2.465l5.555 3.703c.742.495 1.435 1.104 1.957 1.832Zm-2 2v5a1 1 0 0 0 2 0v-5h8.098c-.06.268-.196.513-.391.707l-7 7a2.4 2.4 0 0 1-.695.485c.016.124.05.246.105.358c.08.164.202.303.34.42c.427.36 1.002.551 1.536.685C16.29 19.979 17.669 20 19 20a1 1 0 0 1 0 2c-2.399 0-6.463-.087-7.679-2.57a3.2 3.2 0 0 1-.316-1.23a2.4 2.4 0 0 1-.712-.493l-7-7A1.44 1.44 0 0 1 2.902 10Z");
}

</style>
