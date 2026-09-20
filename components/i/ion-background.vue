<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wdiwhac6u"/><path class="xjcahy9up"/><path class="pi-kv8q6n"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ion-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pi-kv8q6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.909 13.59a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wdiwhac6u {
  fill: var(--svg-color--55b8e3, #55b8e3);
  d: path("M24 0H0v24h24z");
}

.xjcahy9up {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.201 14.188A1.972 1.972 0 0 1 4 12.225a1.97 1.97 0 0 1 1.951-1.977c.698-3.207 3.542-5.608 6.943-5.608c.634 0 1.25.084 1.836.24a1.962 1.962 0 0 1 3.03-.299c.37.37.576.873.574 1.396c.001.328-.08.652-.236.94A7.13 7.13 0 0 1 20 11.78a7.13 7.13 0 0 1-2.112 5.08c.246.338.378.745.377 1.163A1.973 1.973 0 0 1 16.297 20a1.97 1.97 0 0 1-1.832-1.254a7 7 0 0 1-1.57.175c-3.085 0-5.711-1.975-6.694-4.733m.357-.076c.945 2.595 3.425 4.447 6.336 4.447q.759-.002 1.47-.162a1.97 1.97 0 0 1 1.092-2.16a1.955 1.955 0 0 1 2.193.351a6.77 6.77 0 0 0 1.991-4.808c0-1.752-.662-3.35-1.749-4.552a1.96 1.96 0 0 1-2.278.575A1.97 1.97 0 0 1 14.4 5.977a2 2 0 0 1 .153-.768a6.7 6.7 0 0 0-1.66-.207c-3.211 0-5.9 2.255-6.58 5.276a1.976 1.976 0 0 1 1.623 1.947a1.98 1.98 0 0 1-1.378 1.887");
}

</style>
