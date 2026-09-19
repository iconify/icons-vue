<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="vzboieb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:counterclockwise-arrows-button" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.vzboieb-z {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.3 20.1c1.5-.7 3.2-1 4.9-1c6.6 0 11.9 5.1 11.9 12H52c0-10.8-8.9-19.8-19.8-19.8c-3.8 0-7.6 1.1-10.8 3.2L18 11v13.1h13.5zm9.2 22.5c-1.5.7-3.1 1-4.7 1c-6.6 0-12-5.3-12-12.6H12c0 11.4 8.9 20.8 19.8 20.8c3.7 0 7.2-1.1 10.3-3.1L46 53V38.2H32.6z");
}

</style>
