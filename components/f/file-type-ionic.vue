<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="fdqoa3xwr"/><path class="e-wc84kms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ionic" /></template>
<style>
.e-wc84kms {
  fill: var(--svg-color--4e8ef7, #4e8ef7);
  d: path("M27.688 6.224a1.964 1.964 0 0 0-3.252-1.484a14.013 14.013 0 1 0 2.77 2.77a1.96 1.96 0 0 0 .482-1.286M16.023 29.452a13.529 13.529 0 1 1 8.1-24.362a1.964 1.964 0 0 0 2.738 2.738a13.523 13.523 0 0 1-10.838 21.624");
}

.fdqoa3xwr {
  cx: 16.024px;
  cy: 15.923px;
  r: 5.716px;
  fill: var(--svg-color--4e8ef7, #4e8ef7);
}

</style>
