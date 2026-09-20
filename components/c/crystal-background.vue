<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="mdkxl-5oi"/><path class="y_j1losxo"/><path class="u6ldsgb8k"/><path class="djn9x_bek"/><path class="ba420bc3f"/><path class="ctywrlbop"/><path class="zi501607v"/><path fill="url(#SVGJ3BCke6U)" class="j6o_xr7qh"/></g><defs><linearGradient id="SVGJ3BCke6U" x1="10.546" x2="14.909" y1="13.454" y2="16.121" gradientUnits="userSpaceOnUse"><stop class="c2ivumu1e"/><stop offset="1" class="pq7hpf5cd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crystal-background" /></template>
<style>
.ba420bc3f {
  fill: var(--svg-color--8ac4de, #8ac4de);
  d: path("M12 10.788V7.394l-2.424 4.848l.727.727l-1.455.728l-1.697 4.12l1.94-1.696z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c2ivumu1e {
  stop-color: var(--svg-color--d2edfb, #d2edfb);
}

.ctywrlbop {
  fill: var(--svg-color--58779f, #58779f);
  d: path("M12 10.788V7.394l2.424 4.848l-.727.727l1.455.728l1.697 4.12l-1.94-1.696z");
}

.djn9x_bek {
  fill: var(--svg-color--6a7c8b, #6a7c8b);
  d: path("M6.667 18.06L12 6.91l5.333 11.15z");
}

.ft5dv1b6b {
  fill: none;
}

.j6o_xr7qh {
  d: path("m9.091 16.12l2.91-5.333l2.908 5.334z");
}

.mdkxl-5oi {
  fill: var(--svg-color--d2e2da, #d2e2da);
  d: path("M12 6.909V4L4.242 20l2.425-1.94z");
}

.pq7hpf5cd {
  stop-color: var(--svg-color--91cce5, #91cce5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u6ldsgb8k {
  fill: var(--svg-color--5a687a, #5a687a);
  d: path("M17.333 18.06H6.667L4.242 20h15.515z");
}

.y_j1losxo {
  fill: var(--svg-color--7e8b92, #7e8b92);
  d: path("M12 6.909V4l7.758 16l-2.425-1.94z");
}

.zi501607v {
  fill: var(--svg-color--475985, #475985);
  d: path("M14.909 16.122H9.09l-1.94 1.697h3.637l.727-.728h.97l.727.727h3.636z");
}

</style>
