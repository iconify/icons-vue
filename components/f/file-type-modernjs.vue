<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGGZgGFv9p)" transform="translate(.64 5.15)scale(.67903)"><path clip-rule="evenodd" class="yyn8dfk-x"/></g><defs><clipPath id="SVGGZgGFv9p"><path class="xewuxsbdv"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-modernjs" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xewuxsbdv {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h218v33H0z");
}

.yyn8dfk-x {
  fill: var(--svg-color--4ecaff, #4ecaff);
  fill-rule: evenodd;
  d: path("M8.82 20.29a14.44 14.44 0 0 1 24.4-14.07q-.84.4-1.72.85a12.6 12.6 0 0 0-21.07 12.17q-.83.53-1.6 1.05M43 3.96a.3.3 0 0 0-.24.03a212 212 0 0 0-12.36 5.9l-7.88-3.54a1 1 0 0 0-.94.04a1 1 0 0 0-.51.79l-.76 6.8l-3.77-1.6a1.03 1.03 0 0 0-1.43.81l-.83 5.95a212 212 0 0 0-12.14 8.3a.32.32 0 0 0 .31.56a220 220 0 0 0 20.96-10.6A220 220 0 0 0 43.08 4.53a.32.32 0 0 0-.08-.58M16.3 17.88q1.74-1.08 3.5-2.13l-3.03-1.29zm5.8-3.46a212 212 0 0 1 6.25-3.46l-5.6-2.51Zm10.98 8.54a12.6 12.6 0 0 0 1.7-10.2l1.61-1.06A14.44 14.44 0 0 1 12 25.77l1.73-.86a12.6 12.6 0 0 0 19.35-1.95m8.83 1.4a2.21 2.21 0 1 0-3.68-2.46a2.21 2.21 0 0 0 3.68 2.46M6.99 7.84a1.1 1.1 0 1 1-2.2 0a1.1 1.1 0 0 1 2.2 0");
}

</style>
