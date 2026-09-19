<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="meukw_sob"/><path class="l__obtd-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:gemini" /></template>
<style>
.l__obtd-r {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  d: path("M50 46c-4.1-1.1-8.3-1.9-12.5-2.2V20.2c4.2-.3 8.4-1.1 12.5-2.2c1.8-.5 1.1-3.4-.8-2.9c-11.2 3.1-23.1 3.1-34.3 0c-1.9-.5-2.7 2.4-.9 2.9c4 1.1 8.2 1.8 12.3 2.2v23.6c-4.2.3-8.3 1.1-12.3 2.2c-1.8.5-1.1 3.4.8 2.9c11.2-3.1 23.1-3.1 34.3 0c1.9.6 2.7-2.4.9-2.9zm-20.7-2.4V20.4c1.7.1 3.5.1 5.2 0v23.2c-1.7-.1-3.4-.1-5.2 0z");
}

.meukw_sob {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff8736, #ff8736);
}

</style>
