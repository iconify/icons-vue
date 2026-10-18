<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vsf43xb3g"/><path class="f4m4d2blf"/><path class="i15pseq0z"/><path class="qeqzwbb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sln" /></template>
<style>
.f4m4d2blf {
  fill: var(--svg-color--7252aa, #7252aa);
  d: path("M29.352 6.882a1.155 1.155 0 0 0-1.443.127l-.081.08L8.726 25.406l-.081.081a1.155 1.155 0 0 1-1.502.092l-4.63-3.476a1.155 1.155 0 0 0 1.57-.173c5.601-6.48 11.18-12.981 16.77-19.472c.23-.265.542-.404.888-.404c.231 0 .45.058.636.185z");
}

.i15pseq0z {
  fill: var(--svg-color--ae7fe2, #ae7fe2);
  d: path("M29.364 25.037L22.4 29.679a1.17 1.17 0 0 1-1.525-.208L4.095 9.988a1.155 1.155 0 0 0-1.583-.173l4.643-3.476a1.16 1.16 0 0 1 .693-.231c.3 0 .589.115.808.323l.07.081l19.102 18.317l.08.08a1.155 1.155 0 0 0 1.444.128z");
}

.qeqzwbb1g {
  fill: var(--svg-color--d59dff, #d59dff);
  d: path("M29.872 7.84v16.226a1.16 1.16 0 0 1-.52.97L22.4 29.68a1.16 1.16 0 0 0 .508-.97V3.21a1.18 1.18 0 0 0-.531-.97l6.975 4.643a1.17 1.17 0 0 1 .52.958");
}

.vsf43xb3g {
  fill: var(--svg-color--5e438f, #5e438f);
  d: path("m7.143 25.58l-4.63-3.477a1.16 1.16 0 0 1-.463-.924V10.74a1.16 1.16 0 0 1 .462-.924L7.143 6.34a1.04 1.04 0 0 0-.311.924v17.392a1.05 1.05 0 0 0 .311.924");
}

</style>
