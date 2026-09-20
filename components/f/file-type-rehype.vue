<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bq-lqjy4p"/><path class="imyxz_6dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rehype" /></template>
<style>
.bq-lqjy4p {
  fill: var(--svg-color--d8a303, #d8a303);
  d: path("M13.046 15.584a2.1 2.1 0 0 0-1.231-.3a2.18 2.18 0 0 0-1.751.859a3.6 3.6 0 0 0-.7 2.337V23H7v-9.457h2.361v1.949H9.4a3.27 3.27 0 0 1 1.064-1.556a2.54 2.54 0 0 1 1.6-.559a2.2 2.2 0 0 1 .977.176Z");
}

.imyxz_6dy {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M25 23h-2.361v-5.172q0-2.806-2.067-2.807a2.24 2.24 0 0 0-1.75.813a3.03 3.03 0 0 0-.713 2.078V23h-2.372V9h2.372v6.113h.041a3.81 3.81 0 0 1 3.379-1.791q3.471 0 3.471 3.851Z");
}

</style>
