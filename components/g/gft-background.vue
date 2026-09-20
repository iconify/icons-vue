<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ox8rb8buy"/><path class="dt0zthb8b"/><path class="z7q-7iblf"/><path class="mv24i81zl"/><path class="pn4qnekfc"/><path class="so6airgsb"/><path clip-rule="evenodd" class="we3wpsbxw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gft-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.dt0zthb8b {
  fill: var(--svg-color--3b896a, #3b896a);
  d: path("m7.103 12.663l-1.911-2.187l3.39-.64z");
}

.ft5dv1b6b {
  fill: none;
}

.mv24i81zl {
  fill: var(--svg-color--3b896a, #3b896a);
  d: path("m16.262 17.258l-4.168-2.337l3.369-2.57z");
}

.ox8rb8buy {
  fill: var(--svg-color--dff8da, #dff8da);
  d: path("m12 4.795l6.405 3.6v7.209l-6.4 3.6l-6.41-3.6v-7.21L12 4.8z");
}

.pn4qnekfc {
  fill: var(--svg-color--4cdac7, #4cdac7);
  d: path("m15.595 11.417l-1.284-2.51l3.804.813z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.so6airgsb {
  fill: var(--svg-color--4ed9ab, #4ed9ab);
  d: path("m7.867 11.743l-1.91-2.187l3.39-.64z");
}

.we3wpsbxw {
  fill: var(--svg-color--4edbc8, #4edbc8);
  fill-rule: evenodd;
  d: path("M19.111 8L12 4L4.889 8v8L12 20l7.111-4zm-.889.484L12 4.964l-6.222 3.52v7.027L12 19.031l6.222-3.52z");
}

.z7q-7iblf {
  fill: var(--svg-color--4ed9ab, #4ed9ab);
  d: path("M8.444 17.155V12.12l3.72-6.627l3.156 6.178z");
}

</style>
