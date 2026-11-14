<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stmwitw7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cursor-resize-horizontal" /></template>
<style>
.stmwitw7t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.031 10.409l2.878-2.878q.646-.649 1.494-.299t.847 1.269q0 .749.75.749h6q.75 0 .75-.75q-.001-.917.847-1.268q.848-.35 1.495.3l2.877 2.877q.66.659.66 1.591t-.66 1.591l-2.878 2.878q-.646.649-1.494.299t-.847-1.269q0-.749-.75-.749H9q-.75 0-.75.75q.001.917-.847 1.268q-.848.35-1.495-.3l-2.877-2.877q-.66-.659-.66-1.591t.66-1.591");
}

</style>
