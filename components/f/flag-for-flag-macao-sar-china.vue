<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ikoq85b_s"/><path class="s9hlxbrom"/><path class="vpdgdcysd"/><path class="zb7t4fi3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-macao-sar-china" /></template>
<style>
.ikoq85b_s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--83bf4f, #83bf4f);
}

.s9hlxbrom {
  fill: var(--svg-color--fff, #fff);
  d: path("M37.5 30.4c-.7.2-1.4.5-2 .9c.1-.6.2-1.2.2-1.9c0-3.6-3.6-7.4-3.6-7.4s-3.6 3.9-3.6 7.4c0 .7.1 1.3.2 1.9c-.6-.4-1.3-.8-2.1-1c-3.9-1.1-8.5 1.3-8.5 1.3s3.2 5 7.1 6.1c3.3.9 5.8-1.6 6.7-1.9h.4c1 .4 3.4 2.8 6.7 1.9c3.9-1.1 7.1-6.1 7.1-6.1s-4.8-2.3-8.6-1.2M24.7 48c2.2 1.3 4.6 2 7.3 2s5.1-.7 7.3-2zm-4.4-4c.5.7 1.1 1.4 1.8 2h19.8c.7-.6 1.3-1.3 1.8-2z");
}

.vpdgdcysd {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("m32 18.1l2.5 1.9l-1-3l2.5-1.9l-3-.1l-1-3l-1 3l-3 .1l2.5 1.9l-1 3zm-7.3 1.2l1.8.3l-1.4-1.3l.7-1.8l-1.6 1l-1.4-1.3l.4 1.8l-1.5.9l1.8.3l.4 1.9zm-5.4 5.4l1.8-.8l-1.9-.4l-.3-1.8l-.9 1.5l-1.8-.4l1.3 1.4l-1 1.6l1.8-.7l1.3 1.4zm25.4 0l-.3 1.8l1.3-1.4l1.8.7l-1-1.6l1.3-1.4l-1.8.4l-.9-1.5l-.3 1.8l-1.9.4zm-5.4-5.4l.8 1.8l.4-1.9l1.8-.3l-1.5-.9l.4-1.8l-1.4 1.3l-1.6-1l.7 1.8l-1.4 1.3z");
}

.zb7t4fi3o {
  fill: var(--svg-color--fff, #fff);
  d: path("M46.3 40H35.6c-2.4 0-2.6-1.7-2.6-2h-2c0 .2-.1 2-2.6 2H17.7c.3.7.6 1.4 1 2h9.7c1.8 0 2.9-.6 3.6-1.4c.7.8 1.8 1.4 3.6 1.4h9.7c.4-.6.7-1.3 1-2");
}

</style>
