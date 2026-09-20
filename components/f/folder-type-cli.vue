<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sct5u5bus"/><path class="nab_hkb_r"/><path class="ldnyk_qcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cli" /></template>
<style>
.ldnyk_qcf {
  d: path("M10.5 14.5v16h20v-16Zm19.04 15.093h-18.1V15.407h18.12v14.186Zm-15.58-5.066l.68.622L18.5 21.7l-3.92-3.484l-.68.6l3.24 2.88Zm4.54 1.031h6v.711h-6Z");
}

.nab_hkb_r {
  fill: var(--svg-color--d9b400, #d9b400);
  d: path("M31 14v17H10V14Z");
}

.sct5u5bus {
  fill: var(--svg-color--686868, #686868);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
