<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGsLOx1bGL)" class="w0xzn4h1e"/><defs><linearGradient id="SVGsLOx1bGL" x1="12" x2="12" y1="3" y2="21.005" gradientUnits="userSpaceOnUse"><stop class="r4_qxlbeh"/><stop offset=".13" class="nqwt5jb2r"/><stop offset=".35" class="ll9--ib7o"/><stop offset=".64" class="i84mf0b0d"/><stop offset=".98" class="i1fo_yb_q"/><stop offset="1" class="ax7x9d8wu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:leo" /></template>
<style>
.ax7x9d8wu {
  stop-color: var(--svg-color--eb5c2c, #eb5c2c);
}

.ft5dv1b6b {
  fill: none;
}

.i1fo_yb_q {
  stop-color: var(--svg-color--eb5e2c, #eb5e2c);
}

.i84mf0b0d {
  stop-color: var(--svg-color--f59c2e, #f59c2e);
}

.ll9--ib7o {
  stop-color: var(--svg-color--f7c730, #f7c730);
}

.nqwt5jb2r {
  stop-color: var(--svg-color--f8e330, #f8e330);
}

.r4_qxlbeh {
  stop-color: var(--svg-color--f6e93d, #f6e93d);
}

.w0xzn4h1e {
  d: path("M16.5 10.682V5.668L11.862 3L9.84 4.1l.822.482l1.174-.624L15.5 6.137V10h-2v1.91zM5 10V7.777L8.685 5.52l3.113 1.664l.012-.032l.385-.707l-3.51-1.993L4.032 7.3L4.02 10zm2.729.714l2.771 1.19V10H7.549l-3.517 1.678L4 16.328l2.009 1.414l.536-.735L5 15.897v-3.761zm5.353 8.75l-1.259.514L8.5 18.23v-3.793h-1v4.307L11.778 21l1.618-.655zM18 16.081V14.5h1v2.02l-4.565 3.33l-2.935-2.36v-2.32L8.852 12.5h5.88L12.5 15.163v1.929l1.955 1.517zm.01-9.694L20 7.975v4.68l-3.838 2.392l-.449-.708L19 12.194V8.362l-1.56-1.177l.57-.803z");
}

</style>
