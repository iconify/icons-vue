<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emvbdc0ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-vr-off-20-regular" /></template>
<style>
.emvbdc0ds {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.119-1.119A3.2 3.2 0 0 1 14.75 17h-1.612a3.25 3.25 0 0 1-2.298-.952l-.594-.593a.35.35 0 0 0-.495 0l-.594.593A3.25 3.25 0 0 1 6.86 17H5.25A3.25 3.25 0 0 1 2 13.75V12h-.5a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5h.51a3.25 3.25 0 0 1 2.395-2.888L2.146 2.854a.5.5 0 0 1 0-.707M5.25 6A2.25 2.25 0 0 0 3 8.25v5.5A2.25 2.25 0 0 0 5.25 16h1.61a2.25 2.25 0 0 0 1.59-.66l.594-.593a1.35 1.35 0 0 1 1.91 0l.593.594c.422.422.994.659 1.59.659h1.613q.252-.001.487-.056L5.293 6zm6.25-3a.5.5 0 0 1 .5.5V5h2.75a3.25 3.25 0 0 1 3.24 3h.51a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5H18v1.75c0 .61-.169 1.18-.46 1.668l-.742-.741c.128-.283.202-.596.202-.927v-5.5A2.25 2.25 0 0 0 14.75 6H8.121l-1-1H8V3.5a.5.5 0 0 1 .5-.5zm-4 7a.5.5 0 0 1 0 1h-2a.5.5 0 1 1 0-1zm7 0a.5.5 0 0 1 0 1h-1.379l-.91-.91A.5.5 0 0 1 12.5 10z");
}

</style>
