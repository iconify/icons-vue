<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxzvejbxe"/><linearGradient id="SVGoKyyWbqs" x1="24.809" x2="24.809" y1="24.809" y2="11.113" gradientUnits="userSpaceOnUse"><stop offset="0" class="e825e26io"/><stop offset="1" class="vcr8t9iqi"/></linearGradient><path fill="url(#SVGoKyyWbqs)" class="y5ie2_bzr"/><linearGradient id="SVGgoVFYdsg" x1="7.191" x2="7.191" y1="7.191" y2="24.809" gradientUnits="userSpaceOnUse"><stop offset="0" class="tdx55c_vw"/><stop offset="1" class="opud24xap"/></linearGradient><path fill="url(#SVGgoVFYdsg)" class="jp4t3bbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-textlint" /></template>
<style>
.e825e26io {
  stop-color: var(--svg-color--f28b95, #f28b95);
}

.jp4t3bbcr {
  d: path("M7.191 7.191h17.618v3.922h-6.831V24.81h-3.956V11.113H7.191Z");
}

.opud24xap {
  stop-color: var(--svg-color--3c84b0, #3c84b0);
}

.oxzvejbxe {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M16 32c8.837 0 16-7.163 16-16S24.837 0 16 0S0 7.163 0 16s7.163 16 16 16");
}

.tdx55c_vw {
  stop-color: var(--svg-color--28ebf8, #28ebf8);
}

.vcr8t9iqi {
  stop-color: var(--svg-color--f34c6f, #f34c6f);
}

.y5ie2_bzr {
  d: path("M11.113 11.113H7.191V24.81h17.618v-3.922H11.113Z");
}

</style>
