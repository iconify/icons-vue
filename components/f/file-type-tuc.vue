<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jjul599cj"/><path class="qjh_1be9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tuc" /></template>
<style>
.jjul599cj {
  fill: var(--svg-color--2eb9db, #2eb9db);
  d: path("M9.774 14.626a9.9 9.9 0 0 0 .447 2.942a5.6 5.6 0 0 0 .392 1.074a6 6 0 0 0 11.193-4.165a9.992 9.992 0 0 1-18.573 7.248a15 15 0 0 1-.615-1.66a13.989 13.989 0 0 1 26.172-9.744a10 10 0 0 0-19.016 4.305");
}

.qjh_1be9b {
  fill: var(--svg-color--388bba, #388bba);
  d: path("M30 16.023a13.995 13.995 0 0 1-26.767 5.7a9.992 9.992 0 0 0 18.572-7.248a5.5 5.5 0 0 0-.4-1.065a6 6 0 0 0-11.192 4.164a9.992 9.992 0 0 1 18.572-7.241a15 15 0 0 1 .62 1.658A14 14 0 0 1 30 16.023");
}

</style>
