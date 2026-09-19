<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="g78z7pb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:digit-nine" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.g78z7pb8f {
  fill: var(--svg-color--fff, #fff);
  d: path("m22.6 40.2l5.6-.6c.1 1.2.5 2.1 1.1 2.6s1.3.9 2.3.9c1.2 0 2.2-.6 3-1.7s1.4-3.5 1.6-7.1c-1.4 1.8-3.2 2.6-5.4 2.6c-2.4 0-4.4-1-6.1-2.8c-1.7-1.9-2.6-4.4-2.6-7.4c0-3.2.9-5.7 2.7-7.7c1.8-1.9 4.1-2.9 6.9-2.9c3 0 5.5 1.2 7.5 3.7c1.8 2.3 2.8 6.4 2.8 12c0 5.7-1 9.9-3 12.4S34.3 48 31.1 48c-2.3 0-4.2-.7-5.7-2s-2.4-3.2-2.8-5.8m13-13.1c0-1.9-.4-3.4-1.3-4.5s-1.8-1.6-3-1.6c-1.1 0-1.9.4-2.6 1.3s-1.1 2.3-1.1 4.3s.4 3.5 1.1 4.5c.8.9 1.7 1.4 2.9 1.4c1.1 0 2-.5 2.8-1.4s1.2-2.2 1.2-4");
}

</style>
