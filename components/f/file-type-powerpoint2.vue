<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aax4t1bdh"/><path class="a6z05dbpy"/><path class="hy9smdbtz"/><path class="f0w7d-bpw"/><path class="s2h56ubrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powerpoint2" /></template>
<style>
.a6z05dbpy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.536 6.138h10.5v19.4h-10.5V23h7.634v-1.275h-7.634v-1.59h7.634v-1.272h-7.631q.002-.936-.006-1.87a4.47 4.47 0 0 0 3.82-.375a4.35 4.35 0 0 0 1.959-3.474c-1.4-.01-2.793-.006-4.186-.006c0-1.384.016-2.767-.029-4.148c-.522.1-1.043.21-1.562.321V6.139");
}

.aax4t1bdh {
  fill: var(--svg-color--d33922, #d33922);
  d: path("M18.536 2.321v2.863c3.4.019 7.357-.035 10.754.016c.642 0 .67.568.678 1.064c.054 5.942-.013 12.055.032 18c-.012.234-.006 1.1-.013 1.346c-.022.823-.434.859-1.257.884c-.132 0-.52.006-.648.012c-3.181-.016-6.362-.009-9.546-.009v3.182L2 27.134V4.873z");
}

.f0w7d-bpw {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.1 10.726c1.727.083 3.82-.684 5.252.611c1.371 1.664 1.008 4.724-1.024 5.719A4.7 4.7 0 0 1 9 17.348c0 1.244-.006 2.488 0 3.731q-.947-.082-1.893-.159c-.029-3.4-.035-6.8 0-10.2");
}

.hy9smdbtz {
  fill: var(--svg-color--d33922, #d33922);
  d: path("M20.766 8.324a4.476 4.476 0 0 1 4.186 4.167c-1.4.016-2.793.01-4.189.01V8.324");
}

.s2h56ubrk {
  fill: var(--svg-color--d33922, #d33922);
  d: path("M8.993 12.446c.627-.029 1.4-.143 1.826.445a2.3 2.3 0 0 1 .041 2.087c-.363.655-1.183.592-1.816.668c-.067-1.066-.06-2.131-.051-3.2");
}

</style>
