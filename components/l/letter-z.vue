<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="e_ekdbbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-z" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.e_ekdbbdd {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.8 41.4l14.8-18.8H21.2v-5.1h22v4.9l-15 19h15.1v5.1H20.8z");
}

</style>
