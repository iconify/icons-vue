<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="kuf42lb8e"><path class="x8r3bo3uc"/><path class="ha91qrqnt"/><path class="cz9ayfbgp"/><g class="l5y23ru5w"><path class="uls1b47cj"/><path class="vm-vqp72y"/><path class="c92ti-bbz"/><path class="nmd15lkvr"/><path class="wbx48kn9i"/><path class="pso4q_bpf"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mvtcss" /></template>
<style>
.c92ti-bbz {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.718 21.347h2.319l.16-1.795h-2.479v-1.753h4.395l-.042.47l-.431 4.831h-3.922z");
}

.cz9ayfbgp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: nonzero;
  d: path("m19.285 10.257l-3.833 5.34a1.79 1.79 0 0 1-1.478.766q-.444 0-.829-.203c-.385-.203-.474-.323-.65-.563l-3.854-5.34v8.37H6.667V7.373h.918q.719 0 1.373.338c.654.338.799.537 1.088.935l3.959 5.52l3.928-5.509q.423-.608 1.083-.946c.66-.338.902-.338 1.388-.338h.929v11.254h-2.048z");
}

.ha91qrqnt {
  fill: var(--svg-color--f7394a, #f7394a);
  d: path("M3 2h22v22H3z");
}

.kuf42lb8e {
  fill-rule: evenodd;
  stroke-linejoin: round;
  stroke-miterlimit: 2;
}

.l5y23ru5w {
  fill-rule: nonzero;
}

.nmd15lkvr {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("m23.729 25.899l-.008.002l-1.952-.527l-.125-1.398h-1.759l.245 2.752l3.59.997l.009-.003z");
}

.pso4q_bpf {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M23.724 17.799v1.753H19.49l-.035-.394l-.08-.889l-.042-.47zm-.006 3.548V23.1H21.79l-.035-.394l-.079-.889l-.042-.47z");
}

.uls1b47cj {
  fill: var(--svg-color--1572b6, #1572b6);
  d: path("m17.992 29.292l-1.274-14.291h14l-1.275 14.288l-5.734 1.59z");
}

.vm-vqp72y {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("m23.718 29.664l4.633-1.284l1.09-12.211h-5.723z");
}

.wbx48kn9i {
  fill: var(--svg-color--fff, #fff);
  d: path("m25.888 23.025l-.211 2.347l-1.955.528v1.824l3.593-.996l.027-.296l.305-3.407z");
}

.x8r3bo3uc {
  fill: none;
  d: path("M0 0h32v32H0z");
}

</style>
