<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0eh4j6qv"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jyp-bubble" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f0eh4j6qv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.207 20.433l-.702 3.978c-.234 1.331.655 2.41 1.986 2.41h0c1.332 0 2.601-1.079 2.836-2.41l.702-3.978m-.702 3.978l-.425 2.411m16.361-9.644l-1.488 8.438c-.117.666.327 1.206.993 1.206h.361m5.419-1.217c-.543.727-1.412 1.217-2.31 1.217h0c-1.33 0-2.22-1.08-1.985-2.411l.276-1.567c.235-1.332 1.505-2.411 2.836-2.411h0c1.332 0 2.221 1.08 1.986 2.41l-.138.784h-4.822m-28.04-.783c.235-1.332 1.505-2.411 2.836-2.411h0c1.332 0 2.22 1.08 1.986 2.41l-.276 1.568c-.235 1.331-1.505 2.41-2.836 2.41h0c-1.332 0-2.22-1.079-1.986-2.41m-.425 2.411l1.7-9.644m11.862 5.666c.235-1.332 1.504-2.411 2.836-2.411h0c1.331 0 2.22 1.08 1.986 2.41l-.277 1.568c-.235 1.331-1.504 2.41-2.836 2.41h0c-1.331 0-2.22-1.079-1.986-2.41m-.425 2.411l1.701-9.644m5.527 5.666c.235-1.332 1.504-2.411 2.836-2.411h0c1.331 0 2.22 1.08 1.986 2.41l-.277 1.568c-.235 1.331-1.504 2.41-2.836 2.41h0c-1.331 0-2.22-1.079-1.985-2.41m-.426 2.411l1.701-9.644");
}

</style>
