<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j_e4e7fxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bezier-curve-fill" /></template>
<style>
.j_e4e7fxs {
  fill: currentColor;
  d: path("M221 144.4A96.26 96.26 0 0 0 181 88h59a8 8 0 0 0 0-16h-81a32 32 0 0 0-62 0H16a8 8 0 0 0 0 16h59a96.26 96.26 0 0 0-40 56.4A32 32 0 1 0 71 184h114a32 32 0 1 0 36-39.6M40 192a16 16 0 1 1 16-16a16 16 0 0 1-16 16m88-128a16 16 0 1 1-16 16a16 16 0 0 1 16-16m88 128a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>
