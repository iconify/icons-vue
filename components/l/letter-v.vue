<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="rsd8r_4bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-v" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.rsd8r_4bg {
  fill: var(--svg-color--fff, #fff);
  d: path("M38.4 17.5h6.3l-9.9 29h-5.7l-9.8-29h6.5l6.3 22z");
}

</style>
