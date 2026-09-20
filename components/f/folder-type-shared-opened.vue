<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><clipPath id="SVG3r0EoLIG"><path class="x8r3bo3uc"/></clipPath></defs><g clip-path="url(#SVG3r0EoLIG)"><path class="l9yftnbjd"/><path class="d528ndb-g"/><path class="sqhj29p-g"/><path class="u-jtx5m1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-shared-opened" /></template>
<style>
.d528ndb-g {
  fill: var(--svg-color--9772fb, #9772fb);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2Z");
}

.l9yftnbjd {
  fill: var(--svg-color--9772fb, #9772fb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.sqhj29p-g {
  fill: var(--svg-color--b094ff, #b094ff);
  d: path("M15 11a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4h6.17a3 3 0 1 0 0-2H15a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2h2a4 4 0 0 0-4-4Zm12 20a4 4 0 0 0 4-4v-6a4 4 0 0 0-4-4h-6.17a3 3 0 1 0 0 2H27a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2h-2a4 4 0 0 0 4 4Z");
}

.u-jtx5m1f {
  fill: var(--svg-color--b094ff, #b094ff);
  d: path("M17 26.5v.5h2v-.5Z");
}

.x8r3bo3uc {
  fill: none;
  d: path("M0 0h32v32H0z");
}

</style>
