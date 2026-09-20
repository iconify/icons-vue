<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nuh0lgy2x"/><path class="kunqbzbdw"/><path class="wd71fkisv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-nuget" /></template>
<style>
.kunqbzbdw {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.331 22.813a4.691 4.691 0 1 1-4.69-4.782a4.726 4.726 0 0 1 4.69 4.782m-13.978-12.08a2.987 2.987 0 1 1-2.953 2.983a2.965 2.965 0 0 1 2.957-2.983Z");
}

.nuh0lgy2x {
  fill: var(--svg-color--004880, #004880);
  d: path("M23.376 30h-9.065a6.72 6.72 0 0 1-6.623-6.8v-9.067a6.72 6.72 0 0 1 6.623-6.8h9.065a6.72 6.72 0 0 1 6.624 6.8V23.2a6.72 6.72 0 0 1-6.624 6.8");
}

.wd71fkisv {
  fill: var(--svg-color--004880, #004880);
  d: path("M2 4.444A2.407 2.407 0 1 0 4.406 2A2.426 2.426 0 0 0 2 4.444");
}

</style>
