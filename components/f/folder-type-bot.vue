<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xhn9r9btz"/><path class="nhrwbdbgn"/><path class="q-bzkdkoq"/><path class="d7umjkwky"/><path class="f8i3edczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-bot" /></template>
<style>
.d7umjkwky {
  fill: var(--svg-color--727176, #727176);
  d: path("M14.3 16.3h1.5v3.2h-1.5zm8-4.7h1.6v1.8h-1.6zm7.7 4.7h1.5v3.2H30zm-9 9.3h3.4v1.9H21z");
}

.f8i3edczu {
  fill: var(--svg-color--aeadb3, #aeadb3);
  d: path("M14.6 11h.4v5.6h-.4zm16.2 0h.4v5.6h-.4z");
}

.nhrwbdbgn {
  fill: var(--svg-color--aeadb3, #aeadb3);
  d: path("M15.9 13.4H30v12.2H15.9z");
}

.q-bzkdkoq {
  fill: var(--svg-color--444242, #444242);
  d: path("M24.1 16.3h3.3v2.2h-3.3zm-5.8 0h3.3v2.2h-3.3zm.2 4.5h8.9v1.9h-8.9z");
}

.xhn9r9btz {
  fill: var(--svg-color--55004c, #55004c);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

</style>
