<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ig-clbpyo"/><path class="t1gbn8b5e"/><path class="h-ikevk3y"/><path class="ddap_0b7r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eti-background" /></template>
<style>
.ddap_0b7r {
  fill: var(--svg-color--eef1f8, #eef1f8);
  d: path("M11.06 4.014v4.221H8.705c-.225 0-.47.174-.47.4v1.012h6.73c.428 0 .8-.216.8-.645c0-.428-.372-.767-.8-.767H12.47v-4.22zM8.235 11.53v4.142c0 .22.188.564.423.564h2.4V20h1.412v-3.765h2.508c.433 0 .786-.282.786-.687c0-.41-.353-.725-.786-.725H9.944c-.202 0-.296-.188-.296-.376v-1.153c0-.188.094-.353.291-.353h5.017c.447 0 .81-.221.81-.645c0-.423-.363-.767-.81-.767z");
}

.ft5dv1b6b {
  fill: none;
}

.h-ikevk3y {
  fill: var(--svg-color--333, #333);
  d: path("M11.826 4v4.988h-3.59v6.47h3.143V20A8.01 8.01 0 0 1 4 12.014C4 7.647 7.487 4.094 11.826 4");
}

.ig-clbpyo {
  fill: var(--svg-color--eef1f8, #eef1f8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t1gbn8b5e {
  fill: var(--svg-color--31aaa7, #31aaa7);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
