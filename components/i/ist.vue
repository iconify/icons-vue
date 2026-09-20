<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtPsfrdsr)" class="jbpu7b_9k"/><path fill="url(#SVGQ9uX7dEW)" class="t5g69wfsl"/><path fill="url(#SVG52PDeble)" class="xmjz4lbzo"/><defs><linearGradient id="SVGtPsfrdsr" x1="15.195" x2="4.446" y1="5.197" y2="11.153" gradientUnits="userSpaceOnUse"><stop class="caubetbuc"/><stop offset="1" class="pthg5sbxi"/></linearGradient><linearGradient id="SVGQ9uX7dEW" x1="14.169" x2="5.022" y1="4.581" y2="16.343" gradientUnits="userSpaceOnUse"><stop class="nxysf8bbg"/><stop offset=".68" class="f9_8cbcej"/><stop offset="1" class="cm96zq-jq"/></linearGradient><linearGradient id="SVG52PDeble" x1="8.072" x2="8.072" y1="11.338" y2="19.105" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kg4bobs7w"/><stop offset=".29" class="t4x0gdcjr"/><stop offset=".51" class="m3bf1sbwf"/><stop offset=".75" class="p9-zb1b5b"/><stop offset=".91" class="yw9e1wbgo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ist" /></template>
<style>
.caubetbuc {
  stop-color: var(--svg-color--6b54fe, #6b54fe);
}

.cm96zq-jq {
  stop-color: var(--svg-color--fe8d03, #fe8d03);
}

.f9_8cbcej {
  stop-color: var(--svg-color--fdc142, #fdc142);
}

.ft5dv1b6b {
  fill: none;
}

.jbpu7b_9k {
  d: path("M16.95 7.81c0 2.656-2.214 4.811-4.95 4.811a5 5 0 0 1-2.443-.63l.823-1.093a3.7 3.7 0 0 0 1.62.369c1.99 0 3.6-1.548 3.6-3.46c0-1.909-1.61-3.457-3.6-3.457S8.4 5.898 8.4 7.806c0 .455.09.891.257 1.287l-1.112.815A4.7 4.7 0 0 1 7.05 7.81C7.05 5.156 9.264 3 12 3s4.95 2.156 4.95 4.81");
}

.kg4bobs7w {
  stop-color: var(--svg-color--e2a495, #e2a495);
}

.m3bf1sbwf {
  stop-color: var(--svg-color--fe5602, #fe5602);
}

.nxysf8bbg {
  stop-color: var(--svg-color--be7ffe, #be7ffe);
}

.p9-zb1b5b {
  stop-color: var(--svg-color--fe6502, #fe6502);
}

.pthg5sbxi {
  stop-color: var(--svg-color--fa81cf, #fa81cf);
}

.t4x0gdcjr {
  stop-color: var(--svg-color--fe581b, #fe581b);
}

.t5g69wfsl {
  d: path("M7.05 13.295c0-2.7 2.214-4.896 4.95-4.896c.923 0 1.791.252 2.53.689l-.847 1.066A3.5 3.5 0 0 0 12 9.75c-2.047 0-3.6 1.521-3.6 3.546v2.808c0 2.025 1.553 3.547 3.6 3.547s3.6-1.521 3.6-3.547v-2.808c0-.521-.045-.823-.243-1.273l1.116-.828c.306.639.477 1.35.477 2.101v2.808C16.95 18.808 14.736 21 12 21s-4.95-2.192-4.95-4.897z");
}

.xmjz4lbzo {
  d: path("M7.635 10.982a4.8 4.8 0 0 0-.585 2.313v2.809c0 1.134.387 2.173 1.04 3.001l1.008-.81a3.74 3.74 0 0 1-.698-2.192v-2.808c0-.558.117-1.084.333-1.557z");
}

.yw9e1wbgo {
  stop-color: var(--svg-color--fe9912, #fe9912);
}

</style>
