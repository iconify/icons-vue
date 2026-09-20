<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVG5NiZhbGj" cx="0" cy="0" r="1" gradientTransform="matrix(-28 0 0 -28 30 2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qea20536a"/><stop offset=".504" class="u1ts3dbke"/><stop offset="1" class="z2w67ghwc"/></radialGradient></defs><path class="pbcq3abhv"/><path fill="url(#SVG5NiZhbGj)" transform="translate(10.714 10.714)scale(.64286)" class="pl1ql5bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-kotlin" /></template>
<style>
.pbcq3abhv {
  fill: var(--svg-color--cc7b00, #cc7b00);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
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
