<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="zu35idble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:asterisk" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.zu35idble {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.5 36.3c.4.2.5.5.5.9c0 .5-.3 1.2-1 2.3c-.6 1.1-1.1 1.7-1.5 2c-.4.2-.7.2-1.1 0l-8.6-6.2L35 45.8c.1.4-.1.7-.5.9s-1.3.3-2.5.3s-2.1-.1-2.5-.3s-.6-.5-.5-.9l1.1-10.5l-8.5 6.2c-.3.2-.7.2-1.1 0s-.9-.9-1.5-2c-.6-1-.9-1.8-.9-2.3s.2-.8.5-.9l9.7-4.3l-9.7-4.3c-.4-.2-.6-.5-.5-1c0-.5.3-1.2.9-2.3c.6-1 1.1-1.7 1.5-1.9s.8-.2 1.1 0l8.5 6.2L29 18.3c-.1-.4.1-.7.5-1s1.3-.3 2.5-.3s2.1.1 2.5.3s.6.5.5 1l-1.1 10.5l8.6-6.2c.3-.2.7-.2 1.1 0s.9.9 1.5 2c.6 1 .9 1.8 1 2.2c0 .5-.1.8-.5 1L35.8 32z");
}

</style>
