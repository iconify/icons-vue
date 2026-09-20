<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGKgkSPcib)" class="r4i437pya"/><path class="cq6uvubpl"/></g><defs><linearGradient id="SVGKgkSPcib" x1="20" x2="5.476" y1="9.557" y2="18.475" gradientUnits="userSpaceOnUse"><stop class="dm3v8-f7y"/><stop offset="1" class="hfz1jvlov"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fund-background" /></template>
<style>
.cq6uvubpl {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.301 5.485h10.192l2.303 4.606l-5.222 7.458h-3.147l-5.221-7.458l1.82-3.64h8.743l1.82 3.638l-4.496 6.495h-2.184L6.412 10.09L7.75 7.416h7.297l1.336 2.673l-3.772 5.53h-1.22l-3.771-5.53l.854-1.708h5.848l.853 1.706l-3.173 4.76l-3.174-4.76l.37-.741h4.4l.372.745l-1.98 2.829l-1.63-2.609h1.883v.483H11.23l.783 1.251l1.397-1.996l-.11-.22H9.495l-.111.223L12 13.98l2.616-3.926l-.594-1.19h-5.25l-.594 1.188l3.467 5.086h.71l3.467-5.086l-1.075-2.153h-6.7L6.973 10.05l4.19 6.052h1.677l4.19-6.052l-1.559-3.117H7.324L5.766 10.05l4.912 7.018h2.645l4.912-7.018l-2.04-4.081H6.6L4.559 10.05l5.398 7.981h4.087l5.399-7.98l-2.11-4.217l.433-.216L20 10.088l-5.7 8.427H9.702L4 10.088z");
}

.dm3v8-f7y {
  stop-color: var(--svg-color--3f59a1, #3f59a1);
}

.ft5dv1b6b {
  fill: none;
}

.hfz1jvlov {
  stop-color: var(--svg-color--3b8dce, #3b8dce);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
