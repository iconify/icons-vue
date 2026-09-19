<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ajbrzgbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-u" /></template>
<style>
.ajbrzgbsj {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 17.1h6.2v17.8c0 2 .2 3.4.7 4.4q1.05 2.4 4.8 2.4q3.6 0 4.8-2.4c.5-.9.7-2.4.7-4.4V17.1h6.2V35c0 3.1-.5 5.5-1.4 7.2c-1.8 3.1-5.2 4.7-10.2 4.7s-8.4-1.6-10.2-4.7c-1-1.7-1.4-4.1-1.4-7.2z");
}

.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
