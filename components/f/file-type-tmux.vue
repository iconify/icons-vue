<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sfnthobji"/><path class="y3zxqcc8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tmux" /></template>
<style>
.sfnthobji {
  fill: var(--svg-color--1bb91f, #1bb91f);
  fill-rule: evenodd;
  d: path("M2 22.3h28v5.07A2.63 2.63 0 0 1 27.38 30H4.63A2.62 2.62 0 0 1 2 27.37zm0 0h28v5.25H2z");
}

.y3zxqcc8r {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M16.52 14.25V2h-1.05v25.55h1.05V15.3H30v-1.05zM2 4.63A2.63 2.63 0 0 1 4.62 2h22.75A2.63 2.63 0 0 1 30 4.63v22.92H2z");
}

</style>
