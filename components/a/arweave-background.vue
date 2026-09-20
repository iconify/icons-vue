<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sltbl6b8g"/><path class="x26wf1b3f"/><path class="v7gis9bnc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arweave-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sltbl6b8g {
  fill: var(--svg-color--222326, #222326);
  d: path("M24 0H0v24h24z");
}

.v7gis9bnc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.127 14.408a1.3 1.3 0 0 1-.09-.247a3 3 0 0 1-.065-.295a1.96 1.96 0 0 1-1.074.596a2.3 2.3 0 0 1-.51.054a2.5 2.5 0 0 1-.822-.13c-.234-.078-.45-.2-.639-.36a1.65 1.65 0 0 1-.419-.547a1.6 1.6 0 0 1-.15-.698q0-.918.682-1.418c.458-.336 1.14-.524 2.046-.524h.655v-.324c0-.504-.382-.908-.886-.908c-.304 0-.527.106-.666.238a.68.68 0 0 0-.21.52H9.488q0-.369.16-.702a1.9 1.9 0 0 1 .479-.625q.316-.252.768-.397q.456-.15 1.041-.15q.527 0 .977.129q.457.128.79.38q.334.253.52.64q.189.38.189.886v2.491q0 .468.06.773q.058.306.17.527v.091zm-.835-1.24c.21-.116.361-.27.447-.42v-.963h-.583c-.445 0-1.027.047-1.23.513c-.129.284-.1.643.134.864c.35.323.864.209 1.233.005");
}

.x26wf1b3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 5.257a6.743 6.743 0 1 0 0 13.487a6.743 6.743 0 0 0 0-13.487M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

</style>
