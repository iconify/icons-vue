<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="zm7pkl--t"/><g class="j_-w87b6t"><path class="lay7ig_0q"/><path class="qlf9n2b5b"/><path class="ocv039b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cue" /></template>
<style>
.j_-w87b6t {
  fill: var(--svg-color--232a68, #232a68);
}

.lay7ig_0q {
  d: path("M10.653 13.015c-1.5 0-2.605 1.123-2.605 2.976s1.1 2.975 2.605 2.975c1.272 0 2.203-.798 2.393-1.943l-.883-.003c-.15.742-.772 1.15-1.505 1.15c-.993 0-1.743-.774-1.743-2.179s.747-2.178 1.746-2.178c.738 0 1.358.416 1.501 1.166h.884c-.199-1.24-1.169-1.964-2.394-1.964zm8.476.08v5.792h3.886v-.752h-3.013v-1.773h2.79v-.75h-2.79v-1.764h2.98v-.753zm-5.43 0v3.833c0 1.307 1.017 2.056 2.299 2.056s2.303-.75 2.303-2.056v-3.833h-.874v3.819c0 .812-.653 1.267-1.428 1.267s-1.426-.455-1.426-1.267v-3.819z");
}

.ocv039b_s {
  d: path("M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2m0 26.653C9.012 28.653 3.347 22.988 3.347 16S9.012 3.347 16 3.347S28.653 9.012 28.653 16S22.988 28.653 16 28.653");
}

.qlf9n2b5b {
  d: path("M16 4.097C9.426 4.097 4.097 9.426 4.097 16S9.426 27.903 16 27.903S27.903 22.574 27.903 16S22.573 4.097 16 4.097m0 23.182c-6.23 0-11.28-5.05-11.28-11.28S9.77 4.721 16 4.721S27.28 9.77 27.28 16S22.23 27.28 16 27.28z");
}

.zm7pkl--t {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--d2d2d2, #d2d2d2);
}

</style>
