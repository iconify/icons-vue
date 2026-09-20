<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="aoe0a56nx"/><path class="n7_ucnv-a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:injective-background" /></template>
<style>
.aoe0a56nx {
  fill: var(--svg-color--4d3dff, #4d3dff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.n7_ucnv-a {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.68 4l-.048.098c1.664.737 2.608 2.26 2.608 3.93c0 1.802-1.152 3.44-3.392 4.832l-.368.23c-1.68 1.047-2.528 2.226-2.528 3.651c0 1.834 1.408 3.177 3.344 3.177c3.104 0 6.704-3.39 6.704-7.91c0-.737-.096-1.457-.272-2.145l-.112.033c.048.376.064.655.064.917c0 2.67-1.472 4.962-3.936 6.485l-.24.147c-.528.311-.976.492-1.424.492c-.592 0-1.04-.393-1.04-.967c0-.491.32-.982 1.36-1.605l.304-.18c2.304-1.375 3.584-3.308 3.584-5.453c0-2.719-1.984-4.962-4.608-5.732m-3.36 16l.048-.098c-1.664-.737-2.608-2.26-2.608-3.93c0-1.802 1.152-3.44 3.392-4.832l.368-.229c1.68-1.048 2.528-2.227 2.528-3.652c0-1.834-1.408-3.177-3.344-3.177C7.6 4.082 4 7.472 4 11.992c0 .737.096 1.457.272 2.145l.112-.033a7 7 0 0 1-.064-.917c0-2.67 1.472-4.962 3.936-6.485l.24-.147c.528-.311.976-.492 1.424-.492c.592 0 1.04.394 1.04.967c0 .491-.32.982-1.36 1.605l-.304.18c-2.304 1.375-3.584 3.308-3.584 5.453c0 2.719 1.984 4.962 4.608 5.732");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
