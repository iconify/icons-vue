<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32,"left":31.88};
const content = `<g class="zlh-loubj"><path class="gj4-gk-fq"/><path class="em-by2bzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-packer" /></template>
<style>
.em-by2bzh {
  d: path("M52.87 7.65L43.03 2v3.94l6.68 3.9v11.83l3.16 1.8c1.95 1.12 3.56.5 3.56-1.5v-8.72c-.05-1.95-1.66-4.48-3.56-5.6");
}

.gj4-gk-fq {
  fill-rule: evenodd;
  d: path("m39.33 5.4l9.06 5.27V30l-9.06-5.26z");
}

.zlh-loubj {
  fill: var(--svg-color--02a8ef, #02a8ef);
}

</style>
