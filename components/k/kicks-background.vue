<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcHD7ybQZ)" class="r4i437pya"/><path class="ri7ktzlem"/><path clip-rule="evenodd" class="h4n99q4yj"/><path class="kp00_5b8h"/></g><defs><linearGradient id="SVGcHD7ybQZ" x1="8.87" x2="8.87" y1="9.043" y2="15.304" gradientUnits="userSpaceOnUse"><stop class="oq8n5-bdi"/><stop offset="1" class="m0ptyceir"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kicks-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h4n99q4yj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.737 9.93a1.144 1.144 0 0 1 1.134-.887h1.277c.487 0 .852.424.758.877l-.184.862H9.739a.174.174 0 1 0 0 .348h1.913l-.143.696H9.35c-.521 0-.91-.452-.81-.94zm1.176-.017c0-.098.076-.174.174-.174h.695a.174.174 0 0 1 0 .348h-.695a.174.174 0 0 1-.174-.174");
}

.kp00_5b8h {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.696 9.913l-.254 1.287a.52.52 0 0 0 .508.626h1.6l.233-.87h-1.218l.23-1.043h.219c.296 0 .654-.272.713-.567l.056-.303h-.828l.076-.348h-1.113l-.07.348h-.347l-.153.87zM8.424 12.52h1.141l-.598 2.783h-1.14zm6 .755l.146-.755h-1.036l-.546 2.783h1.036l.119-.591l.347-.355l.627.946h1.196l-1.016-1.576l1.225-1.207a3.5 3.5 0 0 0-2.098.755m-9.878-.755h1.04l-.209 1.044h.33l1.03-1.043h1.106l-1.21 1.419l.845 1.363h-.386c-.529-.216-1.217-.633-1.377-1.259c-.08.017-.265.063-.39.104a.7.7 0 0 0-.177.094c-.077.052-.14.094-.188.063c-.063-.042-.094-.157-.104-.209c.07.035.215.094.236.052c.025-.052-.028-.264-.236-.264c-.209 0-.313.344-.313.633s.208.365.313.365h.02c.143 0 .665-.007.835.341l-.052-.02a1.8 1.8 0 0 0-.619-.16a1.5 1.5 0 0 1-.494-.105c.042.07.167.209.313.209c.16 0 .47.02.626.156H4zm15.385.362l.069-.361h-2.233a.907.907 0 0 0-.898.91v.192c0 .32.244.591.55.637l1.412.215h-1.694a.575.575 0 0 0-.563.494l-.052.334h2.362c.438 0 .72-.351.747-.8l.021-.33c.021-.32-.139-.599-.452-.616l-1.085-.07a.07.07 0 0 1-.062-.07c0-.034.03-.069.069-.069h1.259a.57.57 0 0 0 .553-.466z");
}

.m0ptyceir {
  stop-color: var(--svg-color--e72324, #e72324);
}

.oq8n5-bdi {
  stop-color: var(--svg-color--ff5959, #ff5959);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ri7ktzlem {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.358 9.639l.163-.595H6.01a1.11 1.11 0 0 0-1.096.887L4.71 10.95a.737.737 0 0 0 .73.877h2.362l.372-1.392H7.165l-.185.522h-.897a.208.208 0 0 1-.209-.257l.16-.63a.21.21 0 0 1 .209-.16h1.753c.17 0 .317-.111.362-.271m4.518 3.478l.167-.595h-2.156a1.12 1.12 0 0 0-1.103.887l-.205 1.02a.737.737 0 0 0 .733.876h2.143l.188-.87h-1.687a.21.21 0 0 1-.209-.257l.164-.63a.21.21 0 0 1 .208-.16h1.392c.174 0 .32-.11.362-.271z");
}

</style>
