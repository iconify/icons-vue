<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><circle class="ketqe1bnq"/><path class="nl6pt3b7l"/><path class="c9_z_eb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bell-with-slash" /></template>
<style>
.c9_z_eb-q {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("m9.23 13.474l4.243-4.242l41.294 41.294l-4.242 4.243z");
}

.ketqe1bnq {
  cx: 32px;
  cy: 32px;
  r: 24px;
  fill: var(--svg-color--333, #333);
}

.nl6pt3b7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M42 32c-1.8-3.1-1.5-5.9-1.5-8c0-4.4-2.5-7.1-6.1-8.2c0-1.4-.8-2.6-2.4-2.6s-2.4 1.1-2.4 2.6c-3.6 1.1-6.1 3.8-6.1 8.2c0 2.1.3 4.9-1.5 8c-1.2 2.2-3.9 2.7-3.9 9.1H46c-.1-6.5-2.7-6.9-4-9.1m-9.2 10.9c0 2.4-2 4.4-4.4 4.4s-4.4-2-4.4-4.4z");
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

</style>
