<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqg603bna"/><path class="nab_hkb_r"/><path class="ldnyk_qcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cli-opened" /></template>
<style>
.kqg603bna {
  fill: var(--svg-color--9b9b9b, #9b9b9b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.ldnyk_qcf {
  d: path("M10.5 14.5v16h20v-16Zm19.04 15.093h-18.1V15.407h18.12v14.186Zm-15.58-5.066l.68.622L18.5 21.7l-3.92-3.484l-.68.6l3.24 2.88Zm4.54 1.031h6v.711h-6Z");
}

.nab_hkb_r {
  fill: var(--svg-color--d9b400, #d9b400);
  d: path("M31 14v17H10V14Z");
}

</style>
