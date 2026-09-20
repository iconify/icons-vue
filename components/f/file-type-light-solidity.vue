<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nv47pmzig"/><path class="hso81g_io"/><path class="hw_6rtbza"/><path class="q1fw8vzxk"/><path class="k6wsxdbcu"/><path class="o0vhcdygb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-solidity" /></template>
<style>
.hso81g_io {
  d: path("M15.975 10h9l-4.5-8h-9Z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.hw_6rtbza {
  d: path("m11.477 18l4.5-8l-4.5-8l-4.5 8Z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.k6wsxdbcu {
  d: path("M16.022 22h-9l4.5 8h9Z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.nv47pmzig {
  d: path("m20.477 2l-4.5 8h-9l4.5-8z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.o0vhcdygb {
  d: path("m20.52 14l-4.5 8l4.5 8l4.5-8Z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.q1fw8vzxk {
  d: path("m11.52 30l4.5-8h9l-4.5 8z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

</style>
