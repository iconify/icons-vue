<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lh7qczbxn"/><path clip-rule="evenodd" class="rfrzs8btz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ghx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lh7qczbxn {
  fill: var(--svg-color--e83c41, #e83c41);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rfrzs8btz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.714 4.698a.629.629 0 0 1 1.245-.177l.103.726a6.7 6.7 0 0 1 4.272 1.41a.404.404 0 0 1 .091.53l-.482.794l-.006-.005l-.908 1.48l.002.001l-.244.395l-.06.066c-.31.387-.636.32-.822.199a2.53 2.53 0 1 0 .714 2.634l.048-.071c.24-.401.55-.405.753-.324l.122.065l.018.013v-.003l.377.2l2.38 1.257a.404.404 0 0 1 .196.498a6.77 6.77 0 0 1-2.952 3.457l.11.788a.63.63 0 0 1-1.244.178l-.06-.427a6.7 6.7 0 0 1-1.435.314l.12.537a.63.63 0 0 1-.477.752a.627.627 0 0 1-.75-.477l-.177-.796A6.746 6.746 0 0 1 8.446 6.39l-.012-.048l-.2-.902a.63.63 0 0 1 .477-.752a.627.627 0 0 1 .75.476l.134.606q.584-.246 1.217-.38zm4.19 2.52l-.86 1.452a3.794 3.794 0 1 0 1.436 5.24l1.468.83a5.48 5.48 0 0 1-4.742 2.73a5.48 5.48 0 1 1 2.697-10.25");
}

</style>
