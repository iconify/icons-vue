<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG6sXcGcod"><stop offset="0" class="q8jktib7e"/><stop offset="1" class="s7vrwibvw"/></linearGradient><linearGradient id="SVGf2Z3KbiF" x1="78.57" x2="78.61" y1="121.6" y2="123.7" gradientUnits="userSpaceOnUse" href="#SVG6sXcGcod"/><linearGradient id="SVGsnuxzcYX" x1="78.57" x2="78.58" y1="121.6" y2="124.3" gradientUnits="userSpaceOnUse" href="#SVG6sXcGcod"/></defs><path class="iao69-w1y"/><circle class="td9nzcbwk"/><circle class="zp8dvf_ku"/><g fill="url(#SVGf2Z3KbiF)" transform="translate(-264.4 -407.8)scale(3.512)"><circle class="fjjci7bav"/><circle class="enukjnb0o"/><circle fill="url(#SVGsnuxzcYX)" class="qvu8xacme"/><circle class="f3aomsbta"/><circle class="y97k1bnqb"/><circle class="qg137hb2f"/><circle class="dv3hlib1y"/><circle class="joii87uzo"/><circle class="osk_x-b3m"/><circle class="i7f21i_1w"/><circle class="ia6t63b7k"/><circle class="c1p2d7mbx"/><circle class="b8m4cab8m"/><circle class="gsqmam81c"/><circle class="w9yyn1b7g"/><circle class="hi3bu_5nm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flatbuffers" /></template>
<style>
.b8m4cab8m {
  cx: 80.33px;
  cy: 122.7px;
  r: 0.2px;
}

.c1p2d7mbx {
  cx: 79.25px;
  cy: 123.4px;
  r: 0.2px;
}

.dv3hlib1y {
  cx: 79.91px;
  cy: 124.3px;
  r: 0.14px;
}

.enukjnb0o {
  cx: 79.93px;
  cy: 121.8px;
  r: 0.31px;
}

.f3aomsbta {
  cx: 78.91px;
  cy: 122.6px;
  r: 0.16px;
}

.fjjci7bav {
  cx: 79.22px;
  cy: 121.8px;
  r: 0.18px;
}

.gsqmam81c {
  cx: 80.75px;
  cy: 122.3px;
  r: 0.23px;
}

.hi3bu_5nm {
  cx: 80.42px;
  cy: 122.1px;
  r: 0.35px;
}

.i7f21i_1w {
  cx: 79.61px;
  cy: 123.4px;
  r: 0.22px;
}

.ia6t63b7k {
  cx: 79.85px;
  cy: 123.1px;
  r: 0.22px;
}

.iao69-w1y {
  fill: var(--svg-color--ee2349, #ee2349);
  d: path("M15.98 1.94c.42.22 1.5.8 2.04 1.22q.95.74 1.74 1.71c.33.4.62 1.05.74 1.63c.2.97.06 1.98-.07 2.95c-.24 1.68-1.3 4.93-1.3 4.93s1.3.88 1.86 1.43c.3.29.47.58.63.96c.22.53.32 1.14.33 1.7c0 .3-.05.94-.05.94s-1.28-1.3-2.14-1.58a2.2 2.2 0 0 0-1.5-.02c-.19.08-.2.44-.41.46c-.47.02-1.47 0-1.87 0s-1.4.02-1.88 0c-.2-.02-.22-.38-.4-.46a2.2 2.2 0 0 0-1.52.02c-.85.28-2.13 1.58-2.13 1.58s-.06-.64-.06-.93a5 5 0 0 1 .33-1.7c.16-.39.35-.68.64-.97c.56-.55 1.86-1.43 1.86-1.43s-1.07-3.25-1.3-4.93a9 9 0 0 1-.06-2.95c.11-.58.4-1.23.73-1.63q.8-.98 1.74-1.7c.54-.42 1.62-1 2.05-1.23");
}

.joii87uzo {
  cx: 80.21px;
  cy: 124px;
  r: 0.08px;
}

.osk_x-b3m {
  cx: 79.7px;
  cy: 123.8px;
  r: 0.18px;
}

.q8jktib7e {
  stop-color: var(--svg-color--ff0c0c, #ff0c0c);
}

.qg137hb2f {
  cx: 80.27px;
  cy: 123.7px;
  r: 0.31px;
}

.qvu8xacme {
  cx: 79.27px;
  cy: 122.3px;
  r: 0.42px;
}

.s7vrwibvw {
  stop-color: var(--svg-color--ffc402, #ffc402);
}

.td9nzcbwk {
  cx: 15.99px;
  cy: 7.25px;
  r: 2.75px;
  fill: var(--svg-color--fff, #fff);
}

.w9yyn1b7g {
  cx: 80.59px;
  cy: 123px;
  r: 0.26px;
}

.y97k1bnqb {
  cx: 79.63px;
  cy: 122.9px;
  r: 0.26px;
}

.zp8dvf_ku {
  cx: 16.41px;
  cy: 29.74px;
  r: 0.26px;
  fill: var(--svg-color--ffc402, #ffc402);
}

</style>
