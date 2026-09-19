<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="t4x8odb5g"/><path class="yd_rphbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cancer" /></template>
<style>
.t4x8odb5g {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--f2b200, #f2b200);
}

.yd_rphbhm {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  d: path("M28.3 32.1c2.1-3.5.6-8.1-2.6-10.3c-.3-.2-.6-.4-.9-.5c5.1-2.1 10.9-1.9 16 .6c1.7.8 3.2-1.7 1.5-2.5c-8.2-4-17.4-3-24.5 2.8c-.2.1-.3.3-.4.4c-.5.5-1 1-1.4 1.6c-.1.1-.2.2-.2.3c-.1.1-.1.2-.2.4c-1.6 3.6-.6 7.6 2.8 9.9c3.5 2.4 8 .6 9.9-2.7zm-9.9-6c3.1-5.1 9.8-.4 7.4 4.6c-1.1 2.2-3.7 2.8-5.8 1.7c-2.2-1.3-2.6-4.3-1.6-6.3zM48.3 39c1.6-3.6.6-7.6-2.8-9.9s-7.8-.5-9.8 2.7c-2.1 3.5-.6 8.1 2.6 10.3c.3.2.6.4.9.5c-5.1 2.1-10.9 1.9-16-.6c-1.7-.8-3.2 1.7-1.5 2.5c8.2 4 17.4 3 24.5-2.8c.2-.1.3-.3.4-.4c.5-.5 1-1 1.4-1.6c.1-.1.2-.2.2-.3s0-.2.1-.4zm-10.1-5.7c1.1-2.2 3.7-2.8 5.8-1.7c2.2 1.2 2.6 4.2 1.6 6.3c-3.1 5.2-9.8.5-7.4-4.6z");
}

</style>
