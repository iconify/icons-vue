<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi2mtdb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carpet-persian" /></template>
<style>
.zi2mtdb5k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 3.75h-15q-1.139 0-1.945.805q-.805.806-.805 1.945v11q0 2.75 2.75 2.75h13.999l-.057-.002q-.073-.006-.144-.026t-.137-.053t-.124-.079t-.106-.102t-.085-.12q-.036-.065-.059-.135t-.032-.144q-.008-.073-.003-.147q.146-1.901 1.093-2.847q.998-.999 2.723-.842q.069.006.136.025t.129.05t.118.073t.103.093t.083.111t.062.124q.025.065.038.133t.013.138v-10q0-2.75-2.75-2.75m-3.531 6.659q.66.659.66 1.591t-.66 1.591l-2.378 2.378q-.659.66-1.591.66t-1.591-.66l-2.378-2.378q-.66-.659-.66-1.591t.66-1.591l2.378-2.378q.659-.66 1.591-.66t1.591.66zm6.061 6.621q-.118.118-.275.175t-.323.042q-1.025-.093-1.527.408q-.553.554-.657 1.903q-.011.133-.067.255t-.151.217z");
}

</style>
