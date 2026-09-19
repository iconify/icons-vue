<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="dulv9fbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-p" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.dulv9fbzp {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.4 33.9c-1.7 1.4-4.1 2.1-7.3 2.1h-6v10.4h-6v-29h12.5c2.9 0 5.2.7 6.9 2.2s2.6 3.8 2.6 6.9c-.2 3.6-1 6-2.7 7.4m-4.6-10.4c-.8-.6-1.8-1-3.2-1h-5.5V31h5.5c1.4 0 2.5-.3 3.2-1s1.2-1.8 1.2-3.3c-.1-1.5-.5-2.6-1.2-3.2");
}

</style>
