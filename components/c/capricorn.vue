<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="cl1kncczt"/><path class="ioxderbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:capricorn" /></template>
<style>
.cl1kncczt {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--44618b, #44618b);
}

.ioxderbng {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  d: path("M48 37.4V37c-.4-3.7-3.2-6.1-7-6.3c-2.2-.1-4.1.9-5.4 2.5c-1.3-4.4-2.6-8.7-4-13c-1.5-4.6-7.2-5.1-9.9-2.2c-1-1.2-2.5-1.9-4.2-1.9c-1.9-.1-1.9 2.9 0 2.9c1.4 0 2.6 1 2.7 2.5v21.3c0 1.9 2.9 1.9 2.9 0V21.6c.6-3.3 4.1-3.3 5.5-1.2c.5.8.7 2.1 1 3c.6 2.2 1.3 4.3 2 6.5c.8 2.5 1.6 5.1 2.4 7.6c-.1.3-.1.7-.1.8c-.2.9-.5 1.7-.8 2.6c-.9 2.3-2.6 4.2-5.2 4.2c-1.9.1-1.9 3 0 2.9c3.9-.1 6.5-2.8 7.9-6.2c1.4 1.4 3.3 2.2 5.3 2.3c3.7.2 6.6-2.9 7-6.3c-.1-.1-.1-.2-.1-.4zm-11.1.1v-.2c-.1-4.9 7.9-4.8 8.2.1c-.3 5-7.8 5-8.2.1z");
}

</style>
