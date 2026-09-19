<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="mjcco9bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-n" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.mjcco9bve {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.2 17.5h6.4l11.5 20.2V17.5h5.6v29h-6.1L25.9 25.9v20.6h-5.6z");
}

</style>
