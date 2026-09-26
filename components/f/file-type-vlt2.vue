<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szq-knsiy"/><path class="jv56m5ymi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vlt2" /></template>
<style>
.jv56m5ymi {
  d: path("M21.472 8.833a2.729 2.729 0 1 1 0 5.458c-.434 0-.88.164-1.098.54l-1.79 3.104c-.387.673-.209 1.516.03 2.257a2.729 2.729 0 1 1-5.197 0c.237-.74.415-1.583.027-2.257l-1.79-3.104c-.217-.376-.663-.54-1.097-.54a2.729 2.729 0 1 1 2.598-1.894c-.238.74-.416 1.583-.028 2.257l1.79 3.104c.217.376.663.54 1.098.54c.434 0 .88-.164 1.097-.54l1.79-3.104c.388-.674.21-1.517-.028-2.257a2.73 2.73 0 0 1 2.598-3.564");
}

.szq-knsiy {
  fill: var(--svg-color--fff, #fff);
  d: path("M2 11.297C2 3.64 3.64 2 11.297 2h9.408c7.656 0 9.297 1.64 9.297 9.297v9.408c0 7.656-1.641 9.297-9.297 9.297h-9.408C3.64 30.002 2 28.36 2 20.705z");
}

</style>
