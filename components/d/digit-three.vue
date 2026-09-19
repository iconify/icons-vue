<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="y5udc5b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:digit-three" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.y5udc5b-e {
  fill: var(--svg-color--fff, #fff);
  d: path("m22 39.2l5.6-.7c.2 1.5.7 2.6 1.4 3.4s1.7 1.2 2.8 1.2c1.2 0 2.2-.5 3-1.4s1.2-2.2 1.2-3.8q0-2.25-1.2-3.6c-.8-.9-1.7-1.3-2.9-1.3c-.7 0-1.6.1-2.6.4l.6-4.9c1.6 0 2.8-.3 3.6-1.1s1.2-1.7 1.2-3c0-1.1-.3-1.9-.9-2.5q-.9-.9-2.4-.9c-1.5 0-1.8.4-2.5 1.1s-1.1 1.8-1.3 3.1l-5.3-.9c.4-1.9.9-3.4 1.7-4.5c.7-1.1 1.8-2 3.1-2.7c1.3-.6 2.8-1 4.5-1c2.8 0 5.1.9 6.8 2.8c1.4 1.5 2.1 3.3 2.1 5.2c0 2.8-1.4 4.9-4.3 6.6c1.7.4 3.1 1.2 4.1 2.6c1 1.3 1.5 3 1.5 4.9c0 2.8-1 5.1-2.9 7c-1.7 1.8-4.1 2.8-7 2.8c-2.7 0-5-.8-6.8-2.4c-1.8-1.7-2.8-3.8-3.1-6.4");
}

</style>
