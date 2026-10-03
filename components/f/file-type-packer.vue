<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="zlh-loubj"><path class="oj_9kybcq"/><path class="s9tkpty6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-packer" /></template>
<style>
.oj_9kybcq {
  fill-rule: evenodd;
  d: path("m7.45 5.4l9.06 5.27V30l-9.06-5.26z");
}

.s9tkpty6p {
  d: path("M20.99 7.65L11.15 2v3.94l6.68 3.9v11.83l3.16 1.8c1.95 1.12 3.56.5 3.56-1.5v-8.72c-.05-1.95-1.66-4.48-3.56-5.6");
}

.zlh-loubj {
  fill: var(--svg-color--02a8ef, #02a8ef);
}

</style>
