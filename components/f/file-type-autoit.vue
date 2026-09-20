<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ww9zybbjw"/><path class="zsyp96rba"/><path class="d8fpmkbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-autoit" /></template>
<style>
.d8fpmkbcv {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("m24.576 20.156l-6.4-9.264a3.1 3.1 0 0 0-.819-.819a2.36 2.36 0 0 0-2.442.023a3.5 3.5 0 0 0-.812.8l-6.57 9.26h3.752l4.808-6.8l1.838 2.71q.26.368.544.789t.5.7q-.368-.031-.865-.031h-3.53l-1.914 2.634Z");
}

.ww9zybbjw {
  cx: 16px;
  cy: 16px;
  r: 12.551px;
  fill: var(--svg-color--5d83ac, #5d83ac);
}

.zsyp96rba {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("M2 16a14 14 0 1 1 14 14A14 14 0 0 1 2 16M16 4.789A11.211 11.211 0 1 0 27.211 16A11.21 11.21 0 0 0 16 4.789");
}

</style>
