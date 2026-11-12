<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g__3qf93x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-pump-fill-round" /></template>
<style>
.g__3qf93x {
  fill: currentColor;
  d: path("M7 2h10a5 5 0 0 1 5 5v8a5.01 5.01 0 0 1-4 4.901V21a1 1 0 0 1-2 0v-1H8v1a1 1 0 0 1-2 0v-1.099A5.01 5.01 0 0 1 2 15V7a5 5 0 0 1 5-5m4.997 15H12a6 6 0 1 0 .006-12a6 6 0 0 0-.009 12m3.156-8.462c-1.165-.138-2.647.079-3.509.94c-.211-.639-.207-1.626.113-2.226C11.8 7.172 11.892 7 12 7c1.234 0 2.395.564 3.153 1.538m-4.675 2.818c-.639.211-1.626.207-2.226-.113C8.172 11.2 8 11.108 8 11c0-1.234.564-2.395 1.538-3.153c-.138 1.165.079 2.647.94 3.509m3.984 2.797c.138-1.165-.079-2.647-.94-3.509c.639-.211 1.626-.207 2.226.113c.08.043.252.135.252.243a3.99 3.99 0 0 1-1.538 3.153m-5.615-.691c1.165.138 2.647-.079 3.509-.94c.211.639.207 1.626-.113 2.226c-.043.08-.135.252-.243.252a3.99 3.99 0 0 1-3.153-1.538");
}

</style>
