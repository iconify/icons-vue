<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b-a8vybka"/><path clip-rule="evenodd" class="bjlgabcrx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grin-background" /></template>
<style>
.b-a8vybka {
  fill: var(--svg-color--f8f24f, #f8f24f);
  d: path("M24 0H0v24h24z");
}

.bjlgabcrx {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-4.437-3.491c.045.126.086.244.127.34q.036-.12.071-.254c.219-.795.513-1.866 1.31-2.095c.29 1.255-.096 2.69-.55 3.855l-.036.088c-.203.52-.416 1.066-.975 1.232l-.735-2.26h-.095c-.064.755-.4 1.825-1.1 2.165c-.655-1.275-1.35-2.86-1.01-4.325c.738.214.95 1.184 1.1 1.874v.006h.095c.085-.4.47-1.995 1.085-1.75c.373.147.561.688.713 1.124m-8.685 3.35h-.003l.005.006zm1.287-2.444c-.124.839-.499 2.057-1.287 2.444c-.52-1.28.185-4.63 1.472-5.26l.73 2.25h.095l.007-.03c.103-.472.431-1.98.998-1.98c.313 0 .514.557.625.866l.04.11c.39 1.03.69 2.195.44 3.295c-.64-.32-.867-1.14-1.056-1.825l-.044-.155h-.095c-.045.455-.37 1.885-1 1.8c-.49-.065-.74-1.11-.835-1.515zm6.7 8.48c-3.985 1.81-8.405-.62-9.365-4.905a1.28 1.28 0 0 1 1.125.19c.244.191.398.513.542.813l.108.222a6 6 0 0 0 1.53 1.835c2.745 2.285 6.64 1.02 8.086-1.835l-.8-.065a.35.35 0 0 1-.26-.14a.4.4 0 0 1-.08-.295a.22.22 0 0 1 .125-.165c.474-.215 2.37-1.03 2.564-.53c.185.473-.105 1.116-.28 1.506l-.03.064a6.57 6.57 0 0 1-3.264 3.305");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
