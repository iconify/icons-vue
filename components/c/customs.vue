<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="xy0_tbcsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:customs" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.xy0_tbcsu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.4 43.5h14v6h-14zm-6-14h6v14h-6zM37.2 22c0 4.8 9.6 4.8 9.6 0v-4.8h-9.6l-3.8 2.9h3.8zm9.5-5.7v-3.8H36.2l1 3.8zM33.8 42.1l14.4-14.4H33.8L20.3 41.8H26l7.8-8.2zm0 2.4h16.8v5H33.8zm1.7-1.7h15.1V27.7z");
}

</style>
