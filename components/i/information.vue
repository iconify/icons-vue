<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><path class="xu5vd_bij"/><circle class="c_ararbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:information" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.c_ararbzn {
  cx: 32px;
  cy: 17.2px;
  r: 5px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.xu5vd_bij {
  d: path("M27 27.8h10v24H27z");
}

</style>
