<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMYuIbdUL)" class="r4i437pya"/><path class="sh-6q3bce"/><path class="lu2ghf8pc"/></g><defs><linearGradient id="SVGMYuIbdUL" x1="12" x2="12" y1="4" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="byvjz_twk"/><stop offset=".17" class="fp85m5l-p"/><stop offset=".28" class="d8aa2vczz"/><stop offset=".43" class="q3_sabe0d"/><stop offset=".67" class="o0dig7ehb"/><stop offset="1" class="g-rt16b9f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:copi-background" /></template>
<style>
.byvjz_twk {
  stop-color: var(--svg-color--7c4f14, #7c4f14);
}

.d8aa2vczz {
  stop-color: var(--svg-color--f0b035, #f0b035);
}

.fp85m5l-p {
  stop-color: var(--svg-color--cf8c21, #cf8c21);
}

.ft5dv1b6b {
  fill: none;
}

.g-rt16b9f {
  stop-color: var(--svg-color--3e1e05, #3e1e05);
}

.lu2ghf8pc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.222 4.458c-.724.209-1.426 1.066-1.662 1.6a2.38 2.38 0 0 0-2.115-1.17c-1.885 0-5.556 2.743-5.556 7.779c0 5.004 2.982 6.222 5.556 6.222c1.555 0 2.51-1.009 2.35-1.631c-.08-.307-.044-.916.703-.916c.746 0 .795.458.702.916C17.964 18.4 16.156 20 13.111 20c-3.04 0-5.44-3.658-6.142-5.258c-.56-1.28-1.325-1.751-1.636-1.826c.374-.734 1.245-.765 1.636-.69A7.87 7.87 0 0 1 14.445 4c.933 0 1.648.307 1.884.458c.322-.288.737-.45 1.169-.458c.28 0 .502.222.724.458");
}

.o0dig7ehb {
  stop-color: var(--svg-color--bc7908, #bc7908);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3_sabe0d {
  stop-color: var(--svg-color--734a08, #734a08);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sh-6q3bce {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.778 12.89c.222 3.332 2.418 5.435 3.742 5.968c-1.556.684-5.147.422-5.147-6.173c0-6.627 3.978-8 6.085-8.227l2.102.458l1.662-.458l.445.458c-.56.177-1.387 1.217-1.778 1.75c-.56-1.097-1.889-1.333-2.431-1.333c-2.578 0-4.956 3.445-4.68 7.556");
}

</style>
