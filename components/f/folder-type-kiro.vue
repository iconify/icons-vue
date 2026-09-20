<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6gx3sbeq"/><g transform="translate(13.23 10.8)scale(.64286)"><rect class="nc4qcxl6u"/><path class="yspd4mbsx"/><path class="nbeanqbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-kiro" /></template>
<style>
.a6gx3sbeq {
  fill: var(--svg-color--7f53c0, #7f53c0);
  d: path("M27.67 3.2h-9.2l-2.1 4.2H4.57v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.nbeanqbti {
  d: path("M14.54 12.82c-.76 0-.88-.92-.88-1.46q0-.76.25-1.13a.7.7 0 0 1 .63-.34q.41 0 .66.34q.29.4.29 1.13c0 .91-.36 1.46-.94 1.46zm3.15 0c-.76 0-.88-.92-.88-1.46q0-.76.26-1.13q.22-.34.62-.34c.4 0 .5.12.66.34q.29.4.29 1.13c0 .91-.36 1.46-.94 1.46z");
}

.nc4qcxl6u {
  width: 28px;
  height: 28px;
  fill: var(--svg-color--9046ff, #9046ff);
  rx: 6.07px;
}

.yspd4mbsx {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 19.1c-1.92 4.25 2.17 5.32 5.18 2.83c.89 2.8 4.2.71 5.4-1.45a15 15 0 0 0 1.3-10.63C19 3.02 9.68 3.01 8.08 9.9c-.39 1.2-.4 2.57-.6 4c-.1.71-.19 1.17-.46 1.92c-.16.44-.38.82-.72 1.47c-.54 1-.31 2.95 2.45 1.94z");
}

</style>
