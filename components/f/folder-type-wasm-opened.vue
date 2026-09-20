<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wz11u_bcj"/><path class="pvf-b3but"/><path class="pp87r2b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-wasm-opened" /></template>
<style>
.pp87r2b7s {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.181 21.703h1.193l.816 4.335h.015l.978-4.335h1.116l.884 4.39h.017l.928-4.39h1.17l-1.52 6.373h-1.184l-.877-4.337h-.023l-.939 4.337H17.55zm8.462 0h1.88l1.87 6.373h-1.232l-.406-1.418h-2.143l-.313 1.418h-1.198zm.715 1.571l-.52 2.339h1.62l-.596-2.342z");
}

.pvf-b3but {
  fill: var(--svg-color--654ff0, #654ff0);
  d: path("M23.06 12v.097a2.063 2.063 0 1 1-4.127 0V12H12v18h18V12z");
}

.wz11u_bcj {
  fill: var(--svg-color--8964c1, #8964c1);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

</style>
