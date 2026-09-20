<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="po07g0hal"/><path class="v477teh6h"/><path class="ohedu-beh"/><g class="d5qgzwbhp"><path class="avfd-fbmm"/><path class="sjc_trr9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dbml" /></template>
<style>
.avfd-fbmm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-35px, 1.35px);
  d: path("M16.88 7.26L15.08 14");
}

.d5qgzwbhp {
  stroke: var(--svg-color--fff, #fff);
}

.ohedu-beh {
  fill: var(--svg-color--96c0ff, #96c0ff);
  d: path("M6.9 13.47v3.47c0 1.02 3.53 2.5 9.08 2.5s9.08-1.48 9.08-2.5v-3.47c-1.73 1.34-5.07 2.21-9.08 2.21s-7.35-.87-9.09-2.2");
}

.po07g0hal {
  fill: var(--svg-color--0246cc, #0246cc);
  d: path("M30 7.24C30 4.34 27.65 2 24.76 2H7.24A5.24 5.24 0 0 0 2 7.24v17.52C2 27.66 4.35 30 7.24 30h17.52c2.9 0 5.24-2.35 5.24-5.24z");
}

.sjc_trr9z {
  fill: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--0-38px, 0.38px);
  d: path("M12.26 12.66h.02l.18.04q.16 0 .27-.12q.11-.13.1-.29v-.12q0-.15-.08-.28a1 1 0 0 0-.23-.19L9.9 10.62l2.6-1.06a.5.5 0 0 0 .34-.47v-.12q0-.16-.1-.3a.4.4 0 0 0-.28-.11l-.18.03h-.01l-3.52 1.5q-.15.06-.24.18a.5.5 0 0 0-.09.29v.15q0 .15.09.28t.24.19zm7.44 0h-.01l-.2.04q-.16 0-.27-.12a.4.4 0 0 1-.1-.29v-.12q0-.15.09-.28a1 1 0 0 1 .23-.19l2.62-1.08l-2.61-1.06a.5.5 0 0 1-.33-.47v-.12q0-.16.1-.3a.4.4 0 0 1 .27-.11l.2.03l3.51 1.5q.16.06.25.18q.09.13.09.29v.15q0 .15-.1.28a1 1 0 0 1-.23.19z");
}

.v477teh6h {
  fill: var(--svg-color--287eff, #287eff);
  d: path("M6.86 19.14v3.1c0 1.03 3.54 2.51 9.08 2.51s9.09-1.48 9.09-2.5v-3.11c-1.87 1.22-5.5 1.85-9.09 1.85c-3.6 0-7.22-.63-9.08-1.85");
}

</style>
