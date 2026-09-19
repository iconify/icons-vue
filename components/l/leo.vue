<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="f0f4r9n8l"/><path class="sc9jr3bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:leo" /></template>
<style>
.f0f4r9n8l {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffce31, #ffce31);
}

.sc9jr3bxk {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  d: path("M43 40.2c-.2.8-.4 1.5-.7 2.3c-.3.7-.6 1.4-1 2c-1.2 2.1-4.6 1.3-4.6-1c.1-3.3 2.7-6.6 4.1-9.5c2.6-5.5 5.2-14.6-1.3-18.9c-4.8-3.2-11.2-1.6-14 3.2c-2.3 4-.4 9.4 1.5 14.2c-3.1-.8-6.4.7-8.1 3.2c-2.2 3.2-.6 7.4 2.6 9.3c3.3 2 7.5.6 9.6-2.2l.3-.3c.1-.1.1-.2.2-.4c.8-1.7.9-3.4.4-5c0-.1 0-.2-.1-.3c-1.7-5.6-9.8-20.6 1.9-20.6c7.2 0 7 5.8 6.2 10.3c-.8 4.1-3 8-5 11.7c-2.1 4-2.6 9.6 2.9 10.9c4.7 1.1 7.2-5 7.9-8.3c.6-1.7-2.4-2.5-2.8-.6zm-21.3-3c2.5-4.5 9.6-.5 7.1 3.9c-2.9 4.2-9.5.5-7.1-3.9z");
}

</style>
