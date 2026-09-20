<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG7zUevewO" x1="-792.28" x2="-793.365" y1="633.265" y2="632.418" gradientTransform="matrix(12.821 0 0 -12.821 10188.143 8132.963)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="sav6x4bmf"/><stop offset="1" class="g_gp7lgqe"/></linearGradient></defs><path class="bmzk_ablp"/><path fill="url(#SVG7zUevewO)" class="yjzo2lbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-bitbucketpipeline" /></template>
<style>
.bmzk_ablp {
  fill: var(--svg-color--2684ff, #2684ff);
  d: path("M2.909 3.41A.9.9 0 0 0 2 4.3a1 1 0 0 0 .012.155L5.82 27.568a1.22 1.22 0 0 0 1.193 1.018h18.269a.9.9 0 0 0 .9-.754l3.805-23.378a.9.9 0 0 0-.737-1.033a1 1 0 0 0-.147-.012Zm16.035 16.709h-5.831l-1.579-8.244h8.823Z");
}

.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

.yjzo2lbwq {
  d: path("M28.776 11.874h-8.419l-1.413 8.244h-5.831L6.228 28.3a1.2 1.2 0 0 0 .785.3h18.274a.9.9 0 0 0 .9-.754Z");
}

</style>
