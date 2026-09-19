<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="sjeg1ybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:digit-seven" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.sjeg1ybal {
  fill: var(--svg-color--fff, #fff);
  d: path("M23 21.8V16h20v4.5c-1.7 1.7-3.3 4.2-5 7.4s-3 6.7-3.9 10.3s-1.3 6.9-1.3 9.7h-5.6c.1-4.5 1-9.1 2.6-13.7c1.6-4.7 3.8-8.8 6.6-12.5z");
}

</style>
