<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="or4uif27k"/><path class="ye3rrjthm"/><path clip-rule="evenodd" class="x_324xb9v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lit-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.or4uif27k {
  fill: var(--svg-color--ff4205, #ff4205);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x_324xb9v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.568 8.007L12.25 4.439a.51.51 0 0 0-.502 0L5.432 8.007a.49.49 0 0 0-.25.425v7.136a.49.49 0 0 0 .25.425l6.317 3.568a.51.51 0 0 0 .502 0l6.317-3.568a.49.49 0 0 0 .251-.425V8.432a.49.49 0 0 0-.251-.425m-6.126-3.891a.9.9 0 0 0-.884 0L5.242 7.684a.86.86 0 0 0-.442.748v7.136c0 .309.168.594.442.748l6.316 3.568a.9.9 0 0 0 .884 0l6.316-3.568a.86.86 0 0 0 .442-.748V8.432a.86.86 0 0 0-.442-.748z");
}

.ye3rrjthm {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.276 9.774s-.015.28-.568 1.19c-.64 1.054-.7 2.288-.046 3.32c1.378 2.172 5.119 2.13 6.506 0c.536-.824.69-1.77.506-2.73c0 0-.443-2.005-1.958-3.27c.023.02.082.288.093.403c.035.352.001.72-.12 1.055c-.088.246-.21.459-.418.623c0-.057-.015-.16-.015-.194c-.01-.7-.287-1.35-.74-1.894c-.394-.476-.935-.8-1.506-1.039c.015.048.041.248.045.287c.03.33.035.794-.01 1.124c-.044.33-.12.51-.223.82c-.157.47-.37.818-.641 1.236c-.05.076-.199.287-.279.393c0 0-.137-.846-.626-1.324");
}

</style>
