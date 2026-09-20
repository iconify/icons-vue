<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="scufjxbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-trending-20-filled" /></template>
<style>
.scufjxbuf {
  fill: currentColor;
  d: path("M2.75 2a.75.75 0 0 1 .75.75v12.5c0 .69.56 1.25 1.25 1.25h12.5a.75.75 0 0 1 0 1.5H4.75A2.75 2.75 0 0 1 2 15.25V2.75A.75.75 0 0 1 2.75 2M12 5.75a.75.75 0 0 1 .75-.75h3.5a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0V7.56l-3.97 3.97a.75.75 0 0 1-1.06 0L9 10.06l-2.22 2.22a.75.75 0 0 1-1.06-1.06l2.75-2.75a.75.75 0 0 1 1.06 0L11 9.94l3.44-3.44h-1.69a.75.75 0 0 1-.75-.75");
}

</style>
