<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cz-qvbcva"/><path class="c3za5vb1y"/><path class="br3pdobze"/><path class="phq5crbma"/><path class="we6tgoupg"/><path class="ar5p6eboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-locale" /></template>
<style>
.ar5p6eboa {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M7.055 13.808c.611-1.573 1.211-3.151 1.821-4.724h1.77c.1.242.189.487.282.73c.447 1.153.887 2.309 1.334 3.463s.879 2.286 1.319 3.429l.356.923h-1.558q-.331-1.011-.658-2.024H7.8q-.326 1.013-.658 2.024H5.588l1.469-3.822m1.181.673h3.051c-.51-1.338-1.014-2.678-1.526-4.015c-.514 1.335-1.017 2.678-1.528 4.016Z");
}

.br3pdobze {
  fill: var(--svg-color--617d8b, #617d8b);
  d: path("M28.233 15.373v-1.094h-5.274v-1.767h-1.712v1.767h-3.366v1.094h6.7a9.7 9.7 0 0 1-1.922 3.38c-1.369-1.619-1.375-2.146-1.375-2.146h-1.422s.059.788 1.978 3.038a14 14 0 0 1-1.1 1.016l.438 1.366s.659-.567 1.487-1.445c.828.9 1.9 1.978 3.279 3.265l.9-.9c-1.481-1.344-2.567-2.41-3.364-3.265a9.9 9.9 0 0 0 2.385-4.315h2.368Z");
}

.c3za5vb1y {
  fill: var(--svg-color--4352b8, #4352b8);
  d: path("m22.041 24.715l-4.755 5.288l-1.731-5.288z");
}

.cz-qvbcva {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M28.137 30A1.854 1.854 0 0 0 30 28.168V9.454a1.854 1.854 0 0 0-1.863-1.835H9.956L17.253 30Z");
}

.phq5crbma {
  fill: var(--svg-color--4f8bf5, #4f8bf5);
  d: path("M3.863 2A1.87 1.87 0 0 0 2 3.863v18.992a1.87 1.87 0 0 0 1.863 1.863h18.181L14.747 2Z");
}

.we6tgoupg {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.989 7.619h11.148A1.854 1.854 0 0 1 30 9.454v11.227Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
