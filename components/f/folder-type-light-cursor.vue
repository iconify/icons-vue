<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbx1ecbib"/><path class="q_f5ecc3f"/><path class="qp7b27bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-cursor" /></template>
<style>
.q_f5ecc3f {
  d: path("m20.576 10.113l-8.217 4.755a.718.72 0 0 0-.359.622v9.59c0 .257.138.493.359.62l8.214 4.758a.855.857 0 0 0 .853 0l8.215-4.757a.718.72 0 0 0 .359-.62V15.49a.718.72 0 0 0-.36-.622l-8.215-4.755a.863.866 0 0 0-.851 0m-7.56 5.32H28.87c.225 0 .367.247.254.442l-7.928 13.77c-.053.093-.195.056-.195-.05v-9.02a.504.506 0 0 0-.253-.438l-7.788-4.506c-.093-.054-.054-.197.053-.197");
}

.qp7b27bms {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.046 25.075c0-3.567-.017-4.634-.073-4.745c-.051-.104-1.178-.784-4.04-2.438c-2.183-1.261-3.97-2.326-3.97-2.365c-.002-.057 1.635-.072 7.994-.072c7.303 0 8.004.008 8.089.093c.051.051.085.139.076.194c-.025.141-7.972 13.935-8.029 13.935c-.025 0-.046-2.07-.047-4.602");
}

.vbx1ecbib {
  fill: var(--svg-color--676767, #676767);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

</style>
