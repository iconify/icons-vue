<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><path class="az4u2n35c"/><path class="eaxxhsw4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:left-luggage" /></template>
<style>
.az4u2n35c {
  d: path("M48.6 52H15.4c-1.9 0-3.4-1.5-3.4-3.3V25.3c0-1.8 1.5-3.3 3.4-3.3h33.2c1.9 0 3.4 1.5 3.4 3.3v23.3c0 1.9-1.5 3.4-3.4 3.4M15.4 24c-.8 0-1.4.6-1.4 1.3v23.3c0 .7.6 1.3 1.4 1.3h33.2c.8 0 1.4-.6 1.4-1.3V25.3c0-.7-.6-1.3-1.4-1.3z");
}

.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.eaxxhsw4e {
  d: path("M47 32h-3v16h3c.6 0 1-.4 1-1V33c0-.6-.4-1-1-1m-9 0v-4c0-1.1-.9-2-2-2h-8c-1.1 0-2 .9-2 2v4h-4v16h20V32zm-2 0h-8v-4h8zm-19 0c-.6 0-1 .4-1 1v14c0 .6.4 1 1 1h3V32zm25-18H27.4c-.7-1.2-2-2-3.4-2c-2.2 0-4 1.8-4 4s1.8 4 4 4c1.5 0 2.8-.8 3.4-2H30l2-2l2 2h2l2-2l2 2h2l2-2zm-19 4c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

</style>
