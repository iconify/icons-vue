<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mfy3n5ymj"/><path fill="url(#SVGLunRaduB)" class="gf7j-nb1z"/><path fill="url(#SVGPpkRxdPF)" class="z317bcbbp"/><path fill="url(#SVGZonP4jXz)" class="xsjswabjn"/><defs><linearGradient id="SVGLunRaduB" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="eovjo6bxs"/><stop offset=".5" class="fgrp8fbcs"/><stop offset="1" class="way122bfl"/></linearGradient><linearGradient id="SVGPpkRxdPF" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".18" class="y_p1xgpdd"/><stop offset="1" class="x14jkoknm"/></linearGradient><linearGradient id="SVGZonP4jXz" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="xzxw2o4tu"/><stop offset=".49" class="xbxg82u2g"/><stop offset="1" class="z0ibpjbqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:brn" /></template>
<style>
.eovjo6bxs {
  stop-color: var(--svg-color--19f1fe, #19f1fe);
}

.fgrp8fbcs {
  stop-color: var(--svg-color--7f6efb, #7f6efb);
}

.ft5dv1b6b {
  fill: none;
}

.gf7j-nb1z {
  d: path("M10.313 10.875L12 8.063l1.687 2.812l-.624 1.39l.624 1.422L12 16.5l-1.687-2.812l.624-1.424zm1.687 4.5l.996-1.687l-.282-.766l-.152.203v-1.226l.36-1.024L12 9.187l-.922 1.688l.36 1.024v1.226l-.152-.203l-.282.765z");
}

.mfy3n5ymj {
  fill: var(--svg-color--0eebff, #0eebff);
  d: path("m6.937 13.884l-.81-1.322L3 17.896L10.313 21l-1.126-1.687l-4.291-1.868zm10.125 0l.81-1.322L21 17.896L13.687 21l1.126-1.687l4.291-1.868z");
}

.way122bfl {
  stop-color: var(--svg-color--8450fd, #8450fd);
}

.x14jkoknm {
  stop-color: var(--svg-color--1ca4fd, #1ca4fd);
}

.xbxg82u2g {
  stop-color: var(--svg-color--6d5ffe, #6d5ffe);
}

.xsjswabjn {
  d: path("M3 5.813L12 21l9-15.187L13.868 3l.944 1.688l4.281 1.569L12 18.379L4.907 6.262l4.28-1.574L10.133 3z");
}

.xzxw2o4tu {
  stop-color: var(--svg-color--c63fff, #c63fff);
}

.y_p1xgpdd {
  stop-color: var(--svg-color--3636e5, #3636e5);
}

.z0ibpjbqs {
  stop-color: var(--svg-color--268ef5, #268ef5);
}

.z317bcbbp {
  d: path("M8.063 9.564L12 3l3.937 6.564l-.742 1.31L12 5.52l-3.195 5.355z");
}

</style>
