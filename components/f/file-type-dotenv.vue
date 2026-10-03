<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="d2kvgvbvc"><path class="rb0pykboi"/><path class="dy67tyskj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dotenv" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.dy67tyskj {
  fill: var(--svg-color--ecd53f, #ecd53f);
  fill-rule: nonzero;
  d: path("M30 2v28H2V2zM14.76 20.54H9.98v6.44h4.9v-1.09h-3.6v-1.75h3.23v-1.08h-3.23v-1.43h3.48zm2.5 0h-1.27v6.44h1.21v-4.2l2.6 4.2h1.3v-6.44h-1.2v4.3zm5.97 0h-1.41l2.3 6.44h1.39l2.3-6.44h-1.37l-1.58 4.76zM8.3 24.96H6.34v1.96H8.3z");
}

.rb0pykboi {
  d: path("M3.17 3.17h25.66v25.66H3.17z");
}

</style>
