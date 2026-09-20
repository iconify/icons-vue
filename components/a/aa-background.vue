<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bx263-bey"/><path class="jw0gxvbrh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aa-background" /></template>
<style>
.bx263-bey {
  fill: var(--svg-color--7aeead, #7aeead);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jw0gxvbrh {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.77 11l.857-1.334l.116.234l.174-.234l2.416 4.667h-1.7c-.056.007-.193-.023-.253-.213c-.047-.147-.667-1.384-1.17-2.37a.54.54 0 0 0-.223-.227a.47.47 0 0 0-.354.183l-.6.854h.764c.533 0 1 .363 1 .886c0 .524-.467.887-1 .887H4.41l1.113-1.667H4.91c-.5 0-.91-.333-.91-.833S4.407 11 4.91 11zm.173 3.18c.35-.087.724-.36.724-.734c0-.373-.374-.646-.724-.733a.884.884 0 0 1 0 1.467m-1.276-1.62h.163l.7-.927a.64.64 0 0 1 .21-.173a.53.53 0 0 0-.44.21l-.357.47zm4.22 1.646h.243L7.897 9.913l-.087.12zm1.446-2.686v.96h1.8a.55.55 0 0 1 .384.52c0 .29-.247.52-.554.52h-2.296v.813h2.58c.806 0 1.42-.5 1.42-1.267c0-.526-.35-.82-.594-1.066c.244-.247.594-.467.594-1.02c0-.767-.614-1.314-1.42-1.314h-2.58v.814h2.296c.307 0 .554.283.554.573c0 .237-.16.4-.387.467zm2.527.48c.3.306.653.6.653 1.066c0 .7-.61 1.12-1.266 1.12H10.82v-.52h2.143c.394 0 .71-.293.71-.666c0-.314-.173-.667-.516-.667H11.5v-.667h1.657c.343 0 .516-.3.516-.613a.733.733 0 0 0-.71-.72H10.82v-.52h2.427c.726 0 1.266.487 1.266 1.167c0 .466-.356.72-.653 1.02m1.473-.947c0-.767.66-1.387 1.474-1.387h2.86v.834h-2.44c-.31 0-.56.21-.56.5c0 .233.166.433.39.5h1.47A1.48 1.48 0 0 1 20 12.946c0 .767-.66 1.387-1.473 1.387h-2.86V13.5h2.44c.31 0 .56-.21.56-.5a.53.53 0 0 0-.39-.5h-1.47a1.48 1.48 0 0 1-1.474-1.447");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
