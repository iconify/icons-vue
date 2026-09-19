<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="b8kaap0ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:digit-four" /></template>
<style>
.b8kaap0ut {
  fill: var(--svg-color--fff, #fff);
  d: path("M33.7 48v-6.4H20v-5.3L34.5 16h5.4v20.2H44v5.4h-4.1V48zm0-11.8V25.3L26 36.2z");
}

.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
