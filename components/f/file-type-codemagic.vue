<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path fill="url(#SVGZEeVremn)" class="st0 tplm1xb2a"/><defs><linearGradient id="SVGZEeVremn" x1="5" x2="95" y1="5" y2="5" gradientTransform="matrix(.31 0 0 .31 .44 .45)" gradientUnits="userSpaceOnUse"><stop class="mksrsfzfb"/><stop offset="1" class="uipw48vus"/></linearGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-codemagic" /></template>
<style>
.mksrsfzfb {
  stop-color: var(--svg-color--ec0c43, #ec0c43);
}

.tplm1xb2a {
  d: path("m28.62 13.8l-6.87-3.37a.28.28 0 0 1-.19-.19l-3.39-6.87C17.74 2.47 16.87 2 16 2s-1.74.47-2.17 1.37l-3.4 6.87a.3.3 0 0 1-.18.2l-6.88 3.38a2.44 2.44 0 0 0 0 4.39l6.88 3.36c.1.03.15.1.19.18l3.39 6.88c.43.9 1.3 1.37 2.2 1.37a2.4 2.4 0 0 0 2.18-1.37l3.36-6.88c.03-.09.1-.15.19-.18l6.87-3.4a2.44 2.44 0 0 0 0-4.38zm-5.13.49l-3.17 2.77a3.87 3.87 0 0 0-1.25 2.14l-.8 4.14a.33.33 0 0 1-.57.16l-2.76-3.18a3.87 3.87 0 0 0-2.15-1.24l-4.14-.81a.33.33 0 0 1-.15-.56l3.17-2.77a3.87 3.87 0 0 0 1.24-2.14l.81-4.14a.33.33 0 0 1 .56-.16l2.8 3.18c.56.62 1.3 1.08 2.15 1.24l4.14.8c.24.07.34.38.12.57");
}

.uipw48vus {
  stop-color: var(--svg-color--fbb03b, #fbb03b);
}

</style>
