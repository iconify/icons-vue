<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biz27zgjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-24-regular" /></template>
<style>
.biz27zgjo {
  fill: currentColor;
  d: path("M13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v3.254a7.5 7.5 0 0 0-1.5-.878V6.25a.75.75 0 0 0-.75-.75h-2.129c-.404.603-1.09 1-1.871 1h-3.5c-.78 0-1.467-.397-1.871-1H6.25a.75.75 0 0 0-.75.75v13.5c0 .414.336.75.75.75h1.897l-.074.248A1.75 1.75 0 0 0 8.17 22H6.25A2.25 2.25 0 0 1 4 19.75V6.25A2.25 2.25 0 0 1 6.25 4h1.764a2.25 2.25 0 0 1 2.236-2zm-3.5 1.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm5.585 5.509a6.5 6.5 0 1 1-3.404 12.22l-2.465.74a.751.751 0 0 1-.935-.934l.739-2.467a6.5 6.5 0 0 1-.766-2.839L9 15.5A6.5 6.5 0 0 1 15.5 9zM15.5 10.5a5 5 0 0 0-5 5l.013.354c.056.816.308 1.577.709 2.237c.11.181.138.4.077.603l-.43 1.437l1.435-.43a.75.75 0 0 1 .605.077a4.97 4.97 0 0 0 2.591.722l.257-.007a5 5 0 0 0 0-9.986z");
}

</style>
