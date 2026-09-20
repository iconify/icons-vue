<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGSGNGmciK)" class="hhyf7opav"/><path fill="url(#SVGHiV83dDD)" class="v4isdzb6o"/><path fill="url(#SVGHTPPTRCb)" clip-rule="evenodd" class="n168k22xb"/><defs><linearGradient id="SVGSGNGmciK" x1="19.528" x2="11.982" y1="9.126" y2="14.55" gradientUnits="userSpaceOnUse"><stop class="iqj7pzb2r"/><stop offset="1" class="qubfbccdf"/></linearGradient><linearGradient id="SVGHiV83dDD" x1="3.06" x2="10.373" y1="15.247" y2="9.575" gradientUnits="userSpaceOnUse"><stop class="i4gb10bpl"/><stop offset="1" class="bm4941zoh"/></linearGradient><linearGradient id="SVGHTPPTRCb" x1="5.17" x2="18.889" y1="12.239" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="efzyhpswx"/><stop offset="1" class="n_h54ab2f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hgpt" /></template>
<style>
.bm4941zoh {
  stop-color: var(--svg-color--675add, #675add);
}

.efzyhpswx {
  stop-color: var(--svg-color--444b8c, #444b8c);
}

.ft5dv1b6b {
  fill: none;
}

.hhyf7opav {
  d: path("M12.03 20.946a8.97 8.97 0 1 0 0-17.94a8.97 8.97 0 0 0 0 17.94");
}

.i4gb10bpl {
  stop-color: var(--svg-color--aa80f9, #aa80f9);
}

.iqj7pzb2r {
  stop-color: var(--svg-color--6767d9, #6767d9);
}

.n_h54ab2f {
  stop-color: var(--svg-color--26264f, #26264f);
}

.n168k22xb {
  fill-rule: evenodd;
  d: path("M17.148 9.864H6.917a1.79 1.79 0 0 0-1.747 1.847c0 1.599 1.235 2.902 2.744 2.902h8.226c1.515 0 2.75-1.303 2.75-2.902a1.8 1.8 0 0 0-1.742-1.847m-6.701 2.66a.96.96 0 0 1-.158.506H7.967a.96.96 0 0 1-.159-.506c0-.597.591-1.077 1.32-1.077c.728 0 1.319.48 1.319 1.077m6.332 0a.96.96 0 0 1-.159.506H14.3a.96.96 0 0 1-.159-.506c0-.597.591-1.077 1.32-1.077c.728 0 1.319.48 1.319 1.077");
}

.qubfbccdf {
  stop-color: var(--svg-color--9578ef, #9578ef);
}

.v4isdzb6o {
  d: path("M17.587 19.02A8.97 8.97 0 1 1 6.52 4.9C7.76 6.53 8.436 8.646 8.024 11c-.074.421-.01.806.153 1.16c.253.56.765 1.045 1.435 1.499c.343.237.739.464 1.145.686c.475.258.971.511 1.488.77c.528.264 1.072.533 1.6.823q.825.452 1.609.976c.422.285.818.597 1.166.934q.555.527.966 1.172");
}

</style>
