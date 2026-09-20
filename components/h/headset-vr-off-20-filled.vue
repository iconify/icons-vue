<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0tni_fhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-vr-off-20-filled" /></template>
<style>
.f0tni_fhm {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.119-1.119A3.2 3.2 0 0 1 14.75 17h-1.612a3.25 3.25 0 0 1-2.298-.952l-.594-.593a.35.35 0 0 0-.495 0l-.594.593A3.25 3.25 0 0 1 6.86 17H5.25A3.25 3.25 0 0 1 2 13.75V12h-.5a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5h.51a3.25 3.25 0 0 1 2.395-2.888L2.146 2.854a.5.5 0 0 1 0-.707M11.5 3a.5.5 0 0 1 .5.5V5h2.75a3.25 3.25 0 0 1 3.24 3h.51a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5H18v1.75c0 .61-.169 1.18-.46 1.668L13.12 11h1.38a.5.5 0 1 0 0-1h-2a.5.5 0 0 0-.288.09L7.122 5H8V3.5a.5.5 0 0 1 .5-.5zm-6 7a.5.5 0 0 0 0 1h2a.5.5 0 1 0 0-1z");
}

</style>
