<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><clipPath id="SVG3r0EoLIG"><path class="x8r3bo3uc"/></clipPath></defs><g clip-path="url(#SVG3r0EoLIG)"><path class="c1ghb6b6f"/><path class="z0w0zkb7y"/><path class="awv1l0b_p"/><path class="wgej8o75l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-common" /></template>
<style>
.awv1l0b_p {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M17.507 22.5a6.01 6.01 0 0 0 4.686 5.85a7.49 7.49 0 0 0 0-11.7a6.01 6.01 0 0 0-4.686 5.85");
}

.c1ghb6b6f {
  fill: var(--svg-color--7c99ac, #7c99ac);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.wgej8o75l {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M16.007 22.5a7.51 7.51 0 0 1 4.5-6.87a7.5 7.5 0 1 0 0 13.74a7.51 7.51 0 0 1-4.5-6.87");
}

.x8r3bo3uc {
  fill: none;
  d: path("M0 0h32v32H0z");
}

.z0w0zkb7y {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M23.507 15a7.45 7.45 0 0 0-3 .63a7.5 7.5 0 0 1 1.684 1.02a6 6 0 1 1 0 11.7a7.5 7.5 0 0 1-1.684 1.02a7.5 7.5 0 1 0 3-14.371Z");
}

</style>
