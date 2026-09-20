<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ag0wm3bwn"/><path class="p_xl5kllm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-certificate" /></template>
<style>
.ag0wm3bwn {
  fill: var(--svg-color--574923, #574923);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

.p_xl5kllm {
  fill: var(--svg-color--af9347, #af9347);
  d: path("M23.045 12.658a4.285 4.285 0 0 0-4.269 4.269v3.56h-2.135v9.257h12.813v-9.257H27.32V16.93a4.284 4.284 0 0 0-4.275-4.272m0 1.424a2.84 2.84 0 0 1 2.849 2.827v3.581H20.2v-3.56a2.837 2.837 0 0 1 2.822-2.851h.005Z");
}

</style>
