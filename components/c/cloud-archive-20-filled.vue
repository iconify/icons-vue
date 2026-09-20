<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n_mwvmbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-archive-20-filled" /></template>
<style>
.n_mwvmbsf {
  fill: currentColor;
  d: path("M10 4c2.817 0 4.415 1.923 4.647 4.246h.07c1.242 0 2.322.709 2.88 1.754H11a2 2 0 0 0-1 3.732V15H5.282C3.469 15 2 13.488 2 11.623C2 9.82 3.373 8.347 5.102 8.251l.251-.005C5.587 5.908 7.183 4 10 4m0 8a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1m8 2h-7v3a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2zm-4.5 1h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1");
}

</style>
