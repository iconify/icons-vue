<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f56wwf9-s"/><path class="j8e58actv"/><path class="h-4n4bbya"/><path clip-rule="evenodd" class="gbckmrb8s"/><path clip-rule="evenodd" class="dn8-4gbfk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:2dai-background" /></template>
<style>
.dn8-4gbfk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.582 10.325H7.349v4.465h2.233a2.233 2.233 0 0 0 0-4.465m0 .372h-1.86v3.72h1.86a1.861 1.861 0 0 0 0-3.72");
}

.f56wwf9-s {
  fill: var(--svg-color--f15a38, #f15a38);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.gbckmrb8s {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.837 11.736v1.712c.022.074.149.227.502.227c.436 0 .986-.343.986-1.102c0-.755-.796-1.13-1.168-1.13h-.034a.29.29 0 0 0-.265.182a.3.3 0 0 0-.021.111m.223.205v1.284c.015.059.108.174.354.174c.309 0 .696-.26.696-.83c0-.569-.559-.852-.827-.852h-.022c-.111 0-.2.101-.2.224M4 11.337l1.116-.64h1.43l.803.774v1.25a3 3 0 0 1-.29.238c-.157.12-.298.227-.35.342h.64v1.489h-2.91L4 14.585v-.819c.499-.357 1.533-1.153 1.708-1.473c-.086-.03-.688.171-.975.275l-.41-.275zm.372-.015l.912-.39h1.153l.54.606v.978l-.64.819v.152h.982v.93H4.372v-.636c.387-.227 1.247-.818 1.585-1.369c-.063-.301-.234-.52-.372-.52c-.085 0-.476.126-.781.222l-.209.071z");
}

.h-4n4bbya {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.705 15.534l.978-1.92h1.332l.979 1.92l1.518-2.976h-6.325z");
}

.j8e58actv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.884 9.953H20v5.582h-1.116zm-.744 2.977l-2.791-4.464l-2.79 4.465h1.294l1.496-2.393l1.496 2.393z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
