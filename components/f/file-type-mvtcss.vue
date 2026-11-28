<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="kuf42lb8e"><path class="glhm_4bof"/><path class="n01u_ebhb"/><path class="gvdzo3eaw"/><g class="l5y23ru5w"><path class="hd7wlbc1f"/><path class="ih_805vhv"/><path class="eylrtlwdr"/><path class="fpa1zgbko"/><path class="d1d6plbyy"/><path class="s14nem_rb"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mvtcss" /></template>
<style>
.d1d6plbyy {
  fill: var(--svg-color--fff, #fff);
  d: path("m25.27 22.38l-.2 2.27l-1.9.51v1.77l3.48-.97l.03-.28l.3-3.3z");
}

.eylrtlwdr {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.17 20.75h2.25l.15-1.73h-2.4v-1.7h4.26l-.04.45l-.42 4.68h-3.8z");
}

.fpa1zgbko {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("m23.18 25.16l-1.9-.5l-.12-1.36h-1.7l.24 2.66l3.47.97h.01z");
}

.glhm_4bof {
  fill: none;
  d: path("M.2.08h31v30.99H.2z");
}

.gvdzo3eaw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: nonzero;
  d: path("m18.88 10.02l-3.71 5.17a1.7 1.7 0 0 1-1.43.74q-.43 0-.8-.2c-.38-.2-.47-.31-.64-.54l-3.73-5.17v8.1H6.66V7.22h.89q.7 0 1.33.33c.63.33.77.52 1.05.9l3.84 5.35l3.8-5.33q.4-.6 1.05-.92c.64-.33.87-.33 1.34-.33h.9v10.9h-1.98z");
}

.hd7wlbc1f {
  fill: var(--svg-color--1572b6, #1572b6);
  d: path("M17.63 28.45L16.39 14.6h13.56l-1.24 13.83l-5.55 1.54z");
}

.ih_805vhv {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("m23.17 28.8l4.49-1.24l1.05-11.82h-5.54z");
}

.kuf42lb8e {
  fill-rule: evenodd;
  stroke-linejoin: round;
  stroke-miterlimit: 2;
}

.l5y23ru5w {
  fill-rule: nonzero;
}

.n01u_ebhb {
  fill: var(--svg-color--f7394a, #f7394a);
  d: path("M3.1 2.02h21.31v21.3H3.11z");
}

.s14nem_rb {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M23.18 17.32v1.7h-4.1l-.04-.39l-.07-.86l-.04-.45zm-.01 3.43v1.7H21.3l-.03-.38l-.08-.86l-.04-.46z");
}

</style>
