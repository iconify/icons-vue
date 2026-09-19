<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="f81v8ccpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:digit-five" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.f81v8ccpy {
  fill: var(--svg-color--fff, #fff);
  d: path("m22 39.3l5.7-.6c.2 1.4.6 2.5 1.4 3.3s1.7 1.2 2.8 1.2c1.2 0 2.2-.5 3-1.6c.8-1 1.2-2.6 1.2-4.7c0-2-.4-3.4-1.2-4.4S33 31 31.7 31c-1.6 0-3.1.8-4.4 2.3l-4.6-.7L25.6 16h15.1v5.7H29.9l-.9 5.4c1.3-.7 2.6-1 3.9-1c2.5 0 4.7 1 6.4 3c1.8 2 2.6 4.5 2.6 7.7c0 2.6-.7 5-2.1 7Q36.95 48 31.7 48c-2.7 0-5-.8-6.7-2.4c-1.6-1.6-2.7-3.7-3-6.3");
}

</style>
