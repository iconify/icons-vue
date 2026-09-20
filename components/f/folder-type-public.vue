<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jf_-2ibmc"/><path class="iuq-q4b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-public" /></template>
<style>
.iuq-q4b_d {
  fill: var(--svg-color--aaffa2, #aaffa2);
  d: path("M22.6 16.3a3.79 3.79 0 0 1 1.8 2.8a3.048 3.048 0 1 0-1.8-2.8m-2 6.3a3.1 3.1 0 1 0-3.1-3.1a3.116 3.116 0 0 0 3.1 3.1m1.3.2h-2.6a3.9 3.9 0 0 0-3.9 3.9V30l.2.1a16.1 16.1 0 0 0 5.4.9a9.64 9.64 0 0 0 4.7-.9l.2-.1v-3.2a4.15 4.15 0 0 0-4-4m5.1-3.2h-2.6a3.23 3.23 0 0 1-1.2 2.6a4.62 4.62 0 0 1 3.3 4.5v1a9.8 9.8 0 0 0 4.1-.9l.2-.1v-3.2a3.82 3.82 0 0 0-3.8-3.9m-11.8-.2a3 3 0 0 0 1.6-.5a3.7 3.7 0 0 1 1.4-2.4v-.2a3.1 3.1 0 0 0-6.2 0a3.27 3.27 0 0 0 3.2 3.1m2.7 2.9a4.2 4.2 0 0 1-1.2-2.6h-2.9a3.9 3.9 0 0 0-3.9 3.9v3.2l.2.1a16.3 16.3 0 0 0 4.4.8v-1a4.81 4.81 0 0 1 3.4-4.4");
}

.jf_-2ibmc {
  fill: var(--svg-color--00a23c, #00a23c);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
