<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="pswgdcbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-d" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.pswgdcbub {
  fill: var(--svg-color--fff, #fff);
  d: path("M37.7 18.1c2 .7 3.7 1.9 4.9 3.7c1 1.4 1.7 3 2.1 4.7s.6 3.3.6 4.8c0 3.9-.8 7.1-2.3 9.8c-2.1 3.6-5.3 5.4-9.7 5.4H20.7v-29h12.5q2.7 0 4.5.6m-11.1 4.4v18.9h5.6q4.35 0 6-4.2c.6-1.5.9-3.4.9-5.5c0-3-.5-5.2-1.4-6.8s-2.8-2.4-5.5-2.4z");
}

</style>
