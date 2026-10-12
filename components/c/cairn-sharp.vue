<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="awfd69bug"/><path class="ahtrytg2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cairn-sharp" /></template>
<style>
.ahtrytg2j {
  d: path("m8.49 10.06l.21-.24l.74-.82h4.87l.74.82l.21.24l.74.82l-.74.81l-.21.24l-.74.82H9.44l-.74-.82l-.21-.24l-.74-.81zm1.93-3.55l.24-.27l.66-.74h1.36l.66.74l.24.27l.67.74l-.67.74l-.24.27l-.66.74h-1.36l-.66-.74l-.24-.27l-.67-.74z");
}

.awfd69bug {
  d: path("m3.69 18.08l.04-.04l.93-1.04h14.68l.93 1.04l.04.04l.94 1.05l-.94 1.04l-.04.04l-.93 1.04H4.66l-.93-1.04l-.04-.04l-.94-1.04zm2.43-4.17l.17-.19l.87-.97h8.93l.87.97l.17.19l.87.97l-.87.96l-.17.19l-.87.97H7.16l-.87-.97l-.17-.19l-.87-.96z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
