<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cbouf6imp"/><path class="v0h7a9-uv"/><path class="h-rig3bdh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:es-background" /></template>
<style>
.cbouf6imp {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h-rig3bdh {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.616 14.76l.192.716c.012.04 0 .076-.044.096c-.056.024-.104.02-.14-.024a129 129 0 0 0-3.52-3.592c-.14-.144-.14-.28.005-.42l3.455-3.32c.144-.131.2-.103.176.093q-.043.335-.08.796c-.184 2.18 1.476 3.791 3.52 3.903c1.156.064 2.9-.16 3.12 1.048c.164.924-.564 1.652-1.432 1.852c-1.28.292-2.24-.108-2.872-1.2c-.276-.472-1.68-.288-2.18-.24a.235.235 0 0 0-.204.188a.2.2 0 0 0 0 .1z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v0h7a9-uv {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.5 9.44c.131-.36-.128-.656-.12-1.024q-.001-.079.052-.02L19.9 11.92a.36.36 0 0 1 .071.388a.4.4 0 0 1-.08.112l-3.087 3.016c-.18.172-.24.14-.192-.104c.272-1.352-.24-3.14-1.588-3.772c-1.112-.52-2.72-.508-3.844-.696c-.788-.132-1.432-.768-1.268-1.6c.256-1.308 2.16-1.452 3.152-1.1c.712.256.848.6 1.112 1.176q.09.188.42.22c.3.032.6.04.888.04c.284 0 .564 0 .84-.024a.21.21 0 0 0 .176-.136");
}

</style>
