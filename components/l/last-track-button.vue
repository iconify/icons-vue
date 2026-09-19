<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="d-qw14bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:last-track-button" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.d-qw14bfx {
  fill: var(--svg-color--fff, #fff);
  d: path("M52 46L34.6 32L52 18zm-17.4 0L17.2 32l17.4-14zM12 18h5.2v28H12z");
}

</style>
