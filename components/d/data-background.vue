<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e5ps0zmid"/><path class="mmr3itbal"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:data-background" /></template>
<style>
.e5ps0zmid {
  fill: var(--svg-color--e9570f, #e9570f);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.mmr3itbal {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.176 9.882a4.705 4.705 0 0 1 4.706-4.705v-.942a5.647 5.647 0 0 0-5.647 5.647zm4.706-3.294a3.294 3.294 0 0 0-3.294 3.294h-.94a4.236 4.236 0 0 1 4.234-4.235zm0 1.412A1.88 1.88 0 0 0 12 9.882h-.941a2.823 2.823 0 0 1 2.823-2.823zm-4.235 6.588a4.706 4.706 0 0 1-4.706-4.706H4a5.647 5.647 0 0 0 5.647 5.648zM6.353 9.882a3.294 3.294 0 0 0 3.294 3.295v.94a4.235 4.235 0 0 1-4.235-4.235zm1.412 0a1.883 1.883 0 0 0 1.882 1.883v.941a2.824 2.824 0 0 1-2.823-2.824zm6.588-.47a4.706 4.706 0 0 1 4.706 4.706H20a5.647 5.647 0 0 0-5.647-5.647zm3.294 4.706a3.294 3.294 0 0 0-3.294-3.294v-.942a4.236 4.236 0 0 1 4.235 4.236zm-1.412 0a1.88 1.88 0 0 0-1.882-1.883v-.94a2.823 2.823 0 0 1 2.824 2.823zm-4.706 0A1.883 1.883 0 0 1 9.647 16v.941a2.824 2.824 0 0 0 2.824-2.823zm1.412 0a3.294 3.294 0 0 1-3.294 3.294v.941a4.235 4.235 0 0 0 4.235-4.235zm-3.294 4.706a4.706 4.706 0 0 0 4.706-4.706h.941a5.647 5.647 0 0 1-5.647 5.647z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
