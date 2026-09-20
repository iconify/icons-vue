<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixgqmybhw"/><path class="msypc_bme"/><path class="r29oqjqgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cursor" /></template>
<style>
.ixgqmybhw {
  fill: var(--svg-color--6c6c6c, #6c6c6c);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.msypc_bme {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.576 10.113l-8.217 4.755a.718.72 0 0 0-.359.622v9.59c0 .257.138.493.359.62l8.214 4.758a.855.857 0 0 0 .853 0l8.215-4.757a.718.72 0 0 0 .359-.62V15.49a.718.72 0 0 0-.36-.622l-8.215-4.755a.863.866 0 0 0-.851 0m-7.56 5.32H28.87c.225 0 .367.247.254.442l-7.928 13.77c-.053.093-.195.056-.195-.05v-9.02a.504.506 0 0 0-.253-.438l-7.788-4.506c-.093-.054-.054-.197.053-.197");
}

.r29oqjqgj {
  d: path("M21.047 25.092c0-3.916-.012-4.62-.084-4.757c-.065-.127-.95-.663-4.042-2.45c-2.177-1.257-3.959-2.318-3.96-2.358c0-.057 1.637-.071 7.996-.071c7.192 0 8.005.009 8.086.09c.05.05.09.126.09.17c0 .105-7.956 13.927-8.03 13.953c-.036.012-.056-1.616-.056-4.577");
}

</style>
