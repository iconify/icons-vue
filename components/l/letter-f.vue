<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="hrblobcht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-f" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.hrblobcht {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.7 17.5h20.7v5.1H27.7v6.7h12.9v5H27.7v12.2h-6z");
}

</style>
