<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="zvnk1zb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-zed" /></template>
<style>
.zvnk1zb9a {
  fill: var(--svg-color--ddd, #ddd);
  fill-rule: evenodd;
  stroke: var(--svg-color--faf3f3, #faf3f3);
  stroke-width: var(--svg-stroke-width--0-569px, 0.569px);
  d: path("M4.04 3.12a.92.92 0 0 0-.92.92v20.2H1.28V4.04c0-1.52 1.24-2.76 2.76-2.76h24.6c1.23 0 1.84 1.49.976 2.36l-15.2 15.2h4.28v-1.9h1.84v2.36a1.38 1.38 0 0 1-1.38 1.38h-6.57l-3.16 3.16h14.3v-11.5h1.84v11.5c0 1.02-.824 1.84-1.84 1.84h-16.2l-3.22 3.22h23.5a.92.92 0 0 0 .92-.92V7.78h1.84v20.2c0 1.52-1.24 2.76-2.76 2.76h-24.6c-1.23 0-1.84-1.49-.976-2.36l15.1-15.1h-4.22v1.84h-1.84v-2.3c0-.762.618-1.38 1.38-1.38h6.52l3.22-3.22H8.09v11.5H6.25V8.22c0-1.02.824-1.84 1.84-1.84h16.2l3.22-3.22z");
}

</style>
