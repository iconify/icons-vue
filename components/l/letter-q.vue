<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="q7uiat7vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-q" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.q7uiat7vn {
  fill: var(--svg-color--fff, #fff);
  d: path("M44.9 37.4c-.5 1.7-1.3 3-2.3 4.1l3.3 3.1l-3.1 3.4l-3.5-3.3c-1.1.6-2 1.1-2.8 1.4c-1.3.4-2.9.7-4.7.7c-3.8 0-6.9-1.1-9.4-3.4q-4.5-4.05-4.5-12c0-7.95 1.5-9.3 4.6-12c2.5-2.2 5.6-3.3 9.4-3.3s6.9 1.2 9.4 3.5c2.9 2.7 4.4 6.5 4.4 11.4c.1 2.5-.2 4.7-.8 6.4m-11 3.9c.4-.1.8-.3 1.4-.5l-3-2.8l3.1-3.3l2.9 2.8c.5-.9.8-1.8 1-2.5c.3-1.1.4-2.3.4-3.7c0-3.3-.7-5.8-2-7.5c-1.3-1.8-3.3-2.7-5.8-2.7c-2.4 0-4.3.9-5.7 2.6S24 28 24 31.4c0 4 1 6.8 3.1 8.5c1.3 1.1 2.9 1.7 4.8 1.7c.7 0 1.4-.1 2-.3");
}

</style>
