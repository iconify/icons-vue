<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mcglarbcm"/><path clip-rule="evenodd" class="kglq0de9b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kwai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kglq0de9b {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 9.333h2.793l.28.287l.19-.287h3.387c.117.117.35.35.35.36l.133-.36h1.444l.353.36l.177-.36h3.766l.387.393l.16 2.65l.547-3.043h1.57l.463.36l-.847 4.973h-3.28l-.376-.38V14h-.234l-.256.666h-3.474l-.366-.34v-.566l-.324.906H7.477l-.364-.34l-.516-1.1l-.267 1.44H4.653l-.35-.34l.697-4.18zm4 2.743l.833-1.433v2.9zM4.414 9.5l.767.563l-.714 4.103h1.4l.324-2.063l1.013 2.063H8.92L7.53 11.75L8.937 9.5H7.351l-.997 1.856l.283-1.856zm5.937 0H9v4.666h1.473l.86-2.66v2.66h1.824l1.056-1.89h-.707l.827-2.776h-1.21l-.857 2.76l.087-2.76H11.12l-.867 2.76zm4.13 4.666h-1.304l2.53-2.7h-1L15.901 9.5h.776l.284 4.666h-1.394v-.673h-.853zm2.78 0h1.376l.834-4.666h-1.427z");
}

.mcglarbcm {
  fill: var(--svg-color--fe8302, #fe8302);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
