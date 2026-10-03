<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxwqohbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-railway" /></template>
<style>
.sxwqohbjb {
  fill: var(--svg-color--fff, #fff);
  d: path("M2.1 14L2 15.4h21.3L23 15c-3.6-4.7-5.6-4.3-8.4-4.4H3.1q-.5 1-.7 2h11V14zm21.3 2.8H2l.1 1.1H22q1.3-.1 1.5-1m-20.2 5s3.3 8 12.8 8.1a14 14 0 0 0 12.7-8.2zM16 2A14 14 0 0 0 3.8 9.1h11.4c1.8.1 4 .3 5.8 1.7a19 19 0 0 1 3.2 3.4q1.2 1.7.4 3.5a3 3 0 0 1-2.7 1.7H2.5l.3 1h26.5A14 14 0 0 0 30 16A14 14 0 0 0 16 2");
}

</style>
