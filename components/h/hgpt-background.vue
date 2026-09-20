<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG6YZ1dVsw)" class="oxn90ac-t"/><path fill="url(#SVGa1OiJdGG)" class="u0lqtmhyo"/><path fill="url(#SVGAJZiweJk)" clip-rule="evenodd" class="u3rex7zzm"/></g><defs><linearGradient id="SVG6YZ1dVsw" x1="18.691" x2="11.984" y1="9.445" y2="14.267" gradientUnits="userSpaceOnUse"><stop class="iqj7pzb2r"/><stop offset="1" class="qubfbccdf"/></linearGradient><linearGradient id="SVGa1OiJdGG" x1="4.053" x2="10.554" y1="14.886" y2="9.844" gradientUnits="userSpaceOnUse"><stop class="i4gb10bpl"/><stop offset="1" class="bm4941zoh"/></linearGradient><linearGradient id="SVGAJZiweJk" x1="5.929" x2="18.124" y1="12.212" y2="12.212" gradientUnits="userSpaceOnUse"><stop class="efzyhpswx"/><stop offset="1" class="n_h54ab2f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hgpt-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bm4941zoh {
  stop-color: var(--svg-color--675add, #675add);
}

.efzyhpswx {
  stop-color: var(--svg-color--444b8c, #444b8c);
}

.ft5dv1b6b {
  fill: none;
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

.oxn90ac-t {
  d: path("M12.026 19.951a7.973 7.973 0 1 0 0-15.947a7.973 7.973 0 0 0 0 15.947");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qubfbccdf {
  stop-color: var(--svg-color--9578ef, #9578ef);
}

.u0lqtmhyo {
  d: path("M16.966 18.24A7.974 7.974 0 1 1 7.13 5.688c1.102 1.45 1.703 3.33 1.337 5.423c-.066.375-.01.717.136 1.031c.225.498.68.93 1.276 1.332c.304.212.656.413 1.017.61c.422.23.863.455 1.323.685c.469.235.952.474 1.421.732q.735.401 1.43.868a7.5 7.5 0 0 1 1.037.83c.329.31.617.66.859 1.04");
}

.u3rex7zzm {
  fill-rule: evenodd;
  d: path("M16.576 10.102H7.481a1.59 1.59 0 0 0-1.552 1.641c0 1.421 1.097 2.58 2.439 2.58h7.312c1.346 0 2.444-1.159 2.444-2.58a1.6 1.6 0 0 0-1.548-1.641m-5.957 2.363a.85.85 0 0 1-.14.45H8.415a.85.85 0 0 1-.14-.45c0-.53.524-.956 1.172-.956s1.172.426 1.172.956m5.629 0a.85.85 0 0 1-.14.45h-2.065a.85.85 0 0 1-.14-.45c0-.53.525-.956 1.172-.956c.648 0 1.173.426 1.173.956");
}

</style>
