<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJpzv3b7Q)" class="r4i437pya"/><path clip-rule="evenodd" class="mpzktnclw"/><path class="qm5dglvhs"/><path class="p8hd0wr7p"/></g><defs><linearGradient id="SVGJpzv3b7Q" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ugdas1_pi"/><stop offset=".409" class="e888s1bvb"/><stop offset=".757" class="ql8bzolen"/><stop offset="1" class="vt01peelf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ecoin-background" /></template>
<style>
.e888s1bvb {
  stop-color: var(--svg-color--f9da3b, #f9da3b);
}

.ft5dv1b6b {
  fill: none;
}

.mpzktnclw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 .5a8 8 0 1 0 0-16a8 8 0 0 0-8 8a8 8 0 0 0 8 8");
}

.p8hd0wr7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.125 9C10.122 9 9.207 10.653 9 11.5h6c-.123-.82-1.113-2.5-2.875-2.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ql8bzolen {
  stop-color: var(--svg-color--edc62d, #edc62d);
}

.qm5dglvhs {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.929 5.502c-2.137 0-3.335.93-3.689 1.157l2.331 1.047c.591-.172 1.396-.2 1.725-.193c3.509.227 4.239 3.44 4.165 4.986H8.877c.42 2.009 1.698 2.5 3.253 2.5c1.352 0 2.374-1.045 2.374-1.5h1.58c-.618 2.184-2.428 3.012-3.788 3.012a6 6 0 0 1-1.726-.238L8.23 17.34c1.337 1.007 3.268 1.194 4.067 1.16c4.604 0 6.204-4.138 6.204-6.392c0-5.189-4.267-6.606-6.571-6.606");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ugdas1_pi {
  stop-color: var(--svg-color--cdae26, #cdae26);
}

.vt01peelf {
  stop-color: var(--svg-color--ceaf26, #ceaf26);
}

</style>
