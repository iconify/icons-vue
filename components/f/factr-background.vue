<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y9aa0uijq"/><path class="utox4bewi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:factr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utox4bewi {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.012 4.002l-6.186.533a.906.906 0 0 0-.824.98a.9.9 0 0 0 .157.444l3.53 5.13a.907.907 0 0 0 1.558-.133l2.66-5.637a.915.915 0 0 0-.895-1.312zm-15.011.986l.533 6.186a.907.907 0 0 0 .98.826a.9.9 0 0 0 .444-.154l5.13-3.54a.908.908 0 0 0-.134-1.547L5.318 4.093a.917.917 0 0 0-1.227.426a.9.9 0 0 0-.085.47zM4.98 20l6.187-.518a.9.9 0 0 0 .746-.522a.92.92 0 0 0-.074-.912l-3.541-5.135a.907.907 0 0 0-1.552.133l-2.661 5.653a.917.917 0 0 0 .437 1.215a.9.9 0 0 0 .459.08zM20 19.03l-.523-6.197a.91.91 0 0 0-.981-.827a.85.85 0 0 0-.448.16l-5.136 3.541a.907.907 0 0 0 .134 1.557l5.652 2.65A.918.918 0 0 0 20 19.03");
}

.y9aa0uijq {
  fill: var(--svg-color--5a5beb, #5a5beb);
  d: path("M24 0H0v24h24z");
}

</style>
