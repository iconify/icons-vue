<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sltbl6b8g"/><path class="x26wf1b3f"/><path class="yj0bm0b7t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ar-background" /></template>
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

.x26wf1b3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 5.257a6.743 6.743 0 1 0 0 13.487a6.743 6.743 0 0 0 0-13.487M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.yj0bm0b7t {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.127 14.409a1.3 1.3 0 0 1-.091-.248a3 3 0 0 1-.065-.295a1.96 1.96 0 0 1-1.074.596a2.3 2.3 0 0 1-.51.054a2.5 2.5 0 0 1-.822-.13c-.233-.078-.45-.2-.638-.359a1.65 1.65 0 0 1-.42-.547a1.6 1.6 0 0 1-.15-.699q0-.918.683-1.417c.458-.337 1.14-.525 2.045-.525h.655v-.324c0-.504-.382-.908-.886-.908c-.304 0-.526.106-.666.238a.68.68 0 0 0-.21.521h-1.49q0-.37.16-.703a1.9 1.9 0 0 1 .478-.625q.317-.252.768-.397q.456-.15 1.042-.15q.525 0 .977.129q.457.128.79.381q.332.252.52.639q.189.382.189.886v2.491q0 .468.059.774q.058.307.171.526v.091zm-.835-1.241c.21-.116.36-.27.446-.419v-.964h-.583c-.444 0-1.026.047-1.23.513c-.128.285-.099.643.135.864c.349.323.863.21 1.232.006");
}

</style>
