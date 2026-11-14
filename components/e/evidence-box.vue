<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c816nxo-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:evidence-box" /></template>
<style>
.c816nxo-c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2.75H4.25q-1.036 0-1.768.732T1.75 5.25v.5q0 1.036.732 1.768q.345.344.757.527q-.489.796-.489 2.08v4.75q0 3.375 3.375 3.375H13.5v-1.525q0-1.554 1.099-2.652l1-1q.825-.825 1.651-1.136v-1.812q0-1.284-.489-2.08q.412-.183.757-.527q.732-.732.732-1.768v-.5q0-1.036-.732-1.768T15.75 2.75m-.267 12.207l1-.999q1.767-1.766 3.534-.001l1 1.001q.733.732.733 1.768v3.025q0 1.036-.732 1.768t-1.768.732h-2q-1.036 0-1.768-.732t-.732-1.768v-3.025q0-1.036.733-1.768m1.06 1.061q-.293.292-.293.707v3.025q0 .414.293.707t.707.293h2q.414 0 .707-.293t.293-.707v-3.025q0-.415-.293-.708l-1-.999q-.707-.707-1.414-.001z");
}

</style>
