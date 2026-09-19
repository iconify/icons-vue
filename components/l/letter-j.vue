<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="mpk874v6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-j" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.mpk874v6d {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.6 35.2v.7c0 2.2.3 3.8.7 4.7S30.6 42 32 42q1.95 0 2.7-1.5c.3-.6.4-1.6.4-3V17.1h6.1v20.2c0 2.5-.4 4.4-1.3 5.9c-1.4 2.4-4 3.7-7.6 3.7s-6.2-1-7.4-3c-1.3-2-1.9-4.7-1.9-8.1v-.7h5.6z");
}

</style>
