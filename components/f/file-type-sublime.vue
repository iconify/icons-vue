<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path fill="url(#SVG466uAeIU)" transform="translate(5.221 .176)scale(.59881)" class="x6ijqvl-m"/><path class="bzwty8owb"/><defs><linearGradient id="SVG466uAeIU" x2="1" gradientTransform="matrix(3.0823 -10.306 8.7238 3.5658 19.839 42.498)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h-htnbcov"/><stop offset=".53" class="h79w7ebun"/><stop offset="1" class="y15y19baw"/></linearGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sublime" /></template>
<style>
.bzwty8owb {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M26.344 2.002a.5.5 0 0 0-.107.022L5.762 8.516c-.189.06-.347.222-.444.414a.5.5 0 0 0-.097.307v6.681c0 .127.038.232.1.309c.096.19.254.35.44.41L26.24 23.13c.298.095.541-.096.541-.424V16.07c0-.328-.243-.67-.541-.764l-8.608-2.73l8.606-2.73c.298-.094.54-.435.54-.763V2.447c0-.287-.187-.468-.433-.445z");
}

.h-htnbcov {
  stop-color: var(--svg-color--ff9700, #ff9700);
}

.h79w7ebun {
  stop-color: var(--svg-color--f48e00, #f48e00);
}

.x6ijqvl-m {
  d: path("M35.995 26.563c0-.548-.405-.864-.902-.707L.902 36.698c-.498.158-.902.731-.902 1.278v11.081c0 .548.404.865.902.707l34.191-10.841c.497-.158.902-.731.902-1.279z");
}

.y15y19baw {
  stop-color: var(--svg-color--d06f00, #d06f00);
}

</style>
