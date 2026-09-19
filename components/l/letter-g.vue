<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="w884xqwfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-g" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.w884xqwfk {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.4 26.5c-.5-2-1.6-3.4-3.4-4.2q-1.5-.6-3.3-.6c-2.3 0-4.3.9-5.8 2.6c-1.5 1.8-2.3 4.4-2.3 7.9c0 3.6.8 6.1 2.4 7.6s3.5 2.2 5.6 2.2c2 0 3.7-.6 5-1.8s2.1-2.7 2.4-4.6h-6.7v-4.8h12.1v15.6h-4l-.6-3.6c-1.2 1.4-2.2 2.3-3.2 2.9c-1.6 1-3.6 1.5-5.9 1.5c-3.8 0-7-1.3-9.4-4c-2.6-2.7-3.8-6.3-3.8-11s1.3-8.5 3.9-11.3s6-4.2 10.3-4.2c3.7 0 6.7.9 8.9 2.8s3.5 4.2 3.8 7z");
}

</style>
