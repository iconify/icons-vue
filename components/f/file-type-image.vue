<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="maa7xacmq"/><path class="xct0y-bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-image" /></template>
<style>
.maa7xacmq {
  fill: var(--svg-color--2dcc9f, #2dcc9f);
  d: path("M30 5.851v20.298H2V5.851z");
}

.xct0y-bfd {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.232 8.541a2.2 2.2 0 1 0 1.127.623a2.2 2.2 0 0 0-1.127-.623M18.111 20.1q-2.724-3.788-5.45-7.575L4.579 23.766h10.9q1.316-1.832 2.634-3.663M22.057 16q-2.793 3.882-5.584 7.765h11.169Q24.851 19.882 22.057 16");
}

</style>
