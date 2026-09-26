<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aze43fb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-11-fill" /></template>
<style>
.aze43fb2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6L11 8.268L10.366 7.1699C10.0899 6.6916 9.4783 6.5277 9 6.8039C8.5217 7.08 8.3578 7.6916 8.634 8.1699L11.134 12.5C11.3603 12.892 11.8216 13.0831 12.2588 12.9659C12.696 12.8488 13 12.4526 13 12L13 6Z");
}

</style>
