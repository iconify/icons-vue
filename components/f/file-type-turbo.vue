<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGItQiulID" x1="-209.59" x2="-223.36" y1="167.02" y2="153.25" gradientTransform="matrix(1 0 0 -1 234 178)" gradientUnits="userSpaceOnUse"><stop offset="0" class="y5fb0lpcu"/><stop offset="1" class="ojj18acah"/></linearGradient></defs><path class="wdopuab5v"/><path fill="url(#SVGItQiulID)" class="zd-jwkbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-turbo" /></template>
<style>
.ojj18acah {
  stop-color: var(--svg-color--ff1e56, #ff1e56);
}

.wdopuab5v {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M16.1 6.9a9.1 9.1 0 1 0 9.1 9.1a9.11 9.11 0 0 0-9.1-9.1m0 13.81A4.71 4.71 0 1 1 20.81 16a4.71 4.71 0 0 1-4.71 4.71");
}

.y5fb0lpcu {
  stop-color: var(--svg-color--0096ff, #0096ff);
}

.zd-jwkbgk {
  fill-rule: evenodd;
  d: path("M16.86 5.41V2a14 14 0 0 1 0 28v-3.4a10.62 10.62 0 0 0 0-21.18ZM8.08 23a10.6 10.6 0 0 1-2.57-6.19h-3.4a13.93 13.93 0 0 0 3.56 8.59l2.4-2.4Zm7.26 7v-3.4A10.6 10.6 0 0 1 9.15 24l-2.4 2.4a13.93 13.93 0 0 0 8.59 3.6");
}

</style>
