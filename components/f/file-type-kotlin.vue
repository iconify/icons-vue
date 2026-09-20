<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG5NiZhbGj)" class="pl1ql5bqj"/><defs><radialGradient id="SVG5NiZhbGj" cx="0" cy="0" r="1" gradientTransform="matrix(-28 0 0 -28 30 2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qea20536a"/><stop offset=".504" class="u1ts3dbke"/><stop offset="1" class="z2w67ghwc"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-kotlin" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pl1ql5bqj {
  d: path("M30 30H2V2h28L15.711 15.794z");
}

.qea20536a {
  stop-color: var(--svg-color--e44857, #e44857);
}

.u1ts3dbke {
  stop-color: var(--svg-color--c711e1, #c711e1);
}

.z2w67ghwc {
  stop-color: var(--svg-color--7f52ff, #7f52ff);
}

</style>
