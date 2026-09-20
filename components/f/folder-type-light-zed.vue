<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fqzwkiogm"/><path clip-rule="evenodd" class="p1_xn-b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-zed" /></template>
<style>
.fqzwkiogm {
  fill: var(--svg-color--525252, #525252);
  d: path("M27.347 5.526h-9.3l-2.1 4.2h-11.7v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.p1_xn-b4x {
  fill: var(--svg-color--ddd, #ddd);
  fill-rule: evenodd;
  stroke: var(--svg-color--faf3f3, #faf3f3);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.754 16.052a.485.485 0 0 0-.485.485v10.664H15.3V16.537c0-.803.651-1.454 1.454-1.454h12.988c.648 0 .972.783.514 1.241l-8 8h2.254v-1h.97v1.242a.727.727 0 0 1-.728.727h-3.465l-1.666 1.666h7.555V20.9h.97v6.06a.97.97 0 0 1-.97.97h-8.524l-1.697 1.696h12.402a.485.485 0 0 0 .485-.485V18.476h.97V29.14c0 .804-.651 1.455-1.455 1.455H16.37a.727.727 0 0 1-.514-1.242l7.968-7.968h-2.222v.97h-.97v-1.213c0-.401.326-.727.727-.727h3.435l1.697-1.696h-7.555v6.059h-.97v-6.06a.97.97 0 0 1 .97-.969h8.524l1.697-1.697z");
}

</style>
