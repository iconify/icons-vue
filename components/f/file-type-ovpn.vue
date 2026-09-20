<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qs6m8zbwg"/><path class="s71g82bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ovpn" /></template>
<style>
.qs6m8zbwg {
  fill: var(--svg-color--ff9100, #ff9100);
  d: path("M24 4C12.953 4 4 12.953 4 24c0 7.395 4.023 13.832 9.988 17.297l4.504-7.785C15.211 31.609 13 28.066 13 24c0-6.074 4.926-11 11-11s11 4.926 11 11c0 4.066-2.21 7.61-5.492 9.512l4.504 7.785C39.977 37.832 44 31.395 44 24c0-11.047-8.953-20-20-20");
}

.s71g82bvx {
  fill: var(--svg-color--1a237e, #1a237e);
  d: path("M30 24c0-3.312-2.687-6-6-6c-3.312 0-6 2.688-6 6a6 6 0 0 0 3.852 5.598l-2.559 13.82A20 20 0 0 0 24 44c1.625 0 3.195-.215 4.707-.578l-2.559-13.824A6 6 0 0 0 30 24");
}

</style>
