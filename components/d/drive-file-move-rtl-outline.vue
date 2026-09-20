<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjuioz1cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-move-rtl-outline" /></template>
<style>
.xjuioz1cx {
  fill: currentColor;
  d: path("m12.025 17.025l1.4-1.4L11.8 14H16v-2h-4.2l1.625-1.625l-1.4-1.4L8 13l4.025 4.025ZM4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.588 1.413T20 20H4ZM4 6v12h16V8h-8.825l-2-2H4Zm0 0v12V6Z");
}

</style>
