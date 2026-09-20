<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="qtrtupnxn"/><path class="j6dnup1gg"/><path class="xlyt4nb7m"/><path class="o0x25ab_y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:drep-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.j6dnup1gg {
  fill: var(--svg-color--014a7f, #014a7f);
  d: path("M18.776 9.69c-.8-3.45-4.255-3.885-5.885-3.69l-.255 1c4.925.105 5.185 3.675 4.665 5.386C16.13 15.8 12.37 17 10.87 17h-4l1.515-6.5h-1.4L5.295 18H10c2.7 0 4.19-.7 4.95-1.13c1.655-.94 4.63-3.726 3.83-7.18z");
}

.o0x25ab_y {
  fill: var(--svg-color--014a7f, #014a7f);
  d: path("m8.121 15.999l1.31-5.5h2.315c.64 0 1.74-.066 1.67.75c-.075.884-1.145 1.054-1.67 1.03h-1.85l-.225.96h1.65l.735 2.61c-.235.075-.59.15-.735.15z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qtrtupnxn {
  fill: var(--svg-color--014a7f, #014a7f);
  d: path("m4 18.999l2.205-9.5h2.42l.56-2.5h2.42l.455-1.956c7.1-.52 8.215 3.9 7.89 6.175c-1.045 6.07-6.315 7.78-9.35 7.78z");
}

.xlyt4nb7m {
  fill: var(--svg-color--014a7f, #014a7f);
  d: path("M13.265 8H9.95l-.325 1.5h3.395c.68 0 1.69.355 1.6 1.585c-.1 1.316-1.42 1.995-2.07 2.17l.71 2.18c1.065-.41 3.145-1.95 3.235-4.224c.09-2.276-2.23-3.21-3.235-3.21z");
}

</style>
