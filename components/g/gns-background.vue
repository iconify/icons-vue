<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGv2o5Kcis)" class="r4i437pya"/><path class="ngg5z-b6c"/><path class="fm-h7rbdw"/><path class="l6h1brb6l"/><path clip-rule="evenodd" class="a_qcezg4a"/></g><defs><linearGradient id="SVGv2o5Kcis" x1="18.739" x2="6.93" y1="3.998" y2="15.035" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ctu96is8m"/><stop offset="1" class="plxd1aczk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gns-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ctu96is8m {
  stop-color: var(--svg-color--266e84, #266e84);
}

.fm-h7rbdw {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.176 10.518c.847-.25 1.459-.273 2.14-.273c1.003 0 1.742.254 2.01.565c.18.047.556.202.556.404V15.2c0 .574.357 1.035.94 1.035c.584 0 .942-.46.942-1.035V8.8c0-.367-.198-.706-.518-.89a1.08 1.08 0 0 0-1.04-.023z");
}

.ft5dv1b6b {
  fill: none;
}

.l6h1brb6l {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.513 8.772c.531.141 1.37.513 1.37 1.346v1.068c0 .01 0-.01 0 0v3.99c0 .565.357 1.06.94 1.06c.584 0 .941-.462.941-1.036V8.8c0-.367-.197-.706-.517-.89a1.08 1.08 0 0 0-1.04-.023zm-1.595 5.322l-1.176.687c-.17.1-.25.301-.146.471c.136.226.367.513.696.725c.339.22.701.268.965.258c.179-.014.273-.169.273-.348v-1.44a.4.4 0 0 0-.612-.348z");
}

.ngg5z-b6c {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.251 7.911c.32.189.513.523.513.89v6.4c0 .574-.357 1.035-.94 1.035c-.585 0-.942-.461-.942-1.035v-3.986c0-.315-.565-.513-.847-.367L9.317 12.81a1.064 1.064 0 0 1-1.426-.423a1.02 1.02 0 0 1 .429-1.398l5.896-3.101c.325-.17.72-.16 1.035.023");
}

.plxd1aczk {
  stop-color: var(--svg-color--56dbae, #56dbae);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
