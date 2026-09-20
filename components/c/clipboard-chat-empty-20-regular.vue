<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhf3qccvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-20-regular" /></template>
<style>
.yhf3qccvq {
  fill: currentColor;
  d: path("M11.5 2a1.5 1.5 0 0 1 1.415 1H14.5A1.5 1.5 0 0 1 16 4.5v2.524a6.5 6.5 0 0 0-1-.526V4.5a.5.5 0 0 0-.5-.5h-1.585A1.5 1.5 0 0 1 11.5 5h-3a1.5 1.5 0 0 1-1.415-1H5.5a.5.5 0 0 0-.5.5v12a.5.5 0 0 0 .5.5h.584l-.02.07c-.094.31-.08.635.025.93H5.5A1.5 1.5 0 0 1 4 16.5v-12A1.5 1.5 0 0 1 5.5 3h1.585A1.5 1.5 0 0 1 8.5 2zm-3 1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm4 4a5.5 5.5 0 1 1-2.652 10.315l-2.204.663a.5.5 0 0 1-.623-.622l.662-2.206A5.5 5.5 0 0 1 12.5 7m0 1a4.5 4.5 0 0 0-3.85 6.831a.5.5 0 0 1 .051.403l-.456 1.52l1.52-.456l.102-.02a.5.5 0 0 1 .301.07A4.5 4.5 0 1 0 12.5 8");
}

</style>
