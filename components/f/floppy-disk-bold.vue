<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ah256ka1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:floppy-disk-bold" /></template>
<style>
.ah256ka1r {
  fill: currentColor;
  d: path("m222.14 69.17l-35.31-35.31A19.86 19.86 0 0 0 172.69 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V83.31a19.86 19.86 0 0 0-5.86-14.14M164 204H92v-44h72Zm40 0h-16v-48a20 20 0 0 0-20-20H88a20 20 0 0 0-20 20v48H52V52h119l33 33ZM164 84a12 12 0 0 1-12 12H96a12 12 0 0 1 0-24h56a12 12 0 0 1 12 12");
}

</style>
