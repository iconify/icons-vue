<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f8nmo-d2a"/><path class="zbtz17bzu"/><path class="db_pptb3d"/><path class="i_o95ju3p"/><path class="tomnhb6ea"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gulf-background" /></template>
<style>
.db_pptb3d {
  fill: var(--svg-color--000, #000);
  d: path("M11.556 6.223H12v1.333h-.444zm0 11.555H12V20h-.444zm.889-11.555h.444v1.333h-.444zm0 12h.444V20h-.444zm5.333-9.534l-.325-.244l-.817.889h-1.97v.444h2.17zM6.222 12.245L6.547 12l.818.888h1.968v.445H7.165zm12.445-.933l-.33.244l-.826-.889h-2.844v-.444h3.044zM5.334 14.867l.328.244l.827-.888h2.844v-.445H6.29z");
}

.f8nmo-d2a {
  fill: var(--svg-color--47c9e3, #47c9e3);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.i_o95ju3p {
  fill: var(--svg-color--000, #000);
  d: path("m17.779 12.2l-.33.245l-.826-.89h-2.4v-.444h2.6zM6.223 15.756l.329.244l.827-.889h2.4v-.444h-2.6z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tomnhb6ea {
  fill: var(--svg-color--000, #000);
  d: path("m16.89 13.089l-.355.244l-.876-.889h-1.88V12h2.093zm-9.778 3.555l.356.245l.875-.889h1.88v-.444H8.13z");
}

.zbtz17bzu {
  fill: var(--svg-color--000, #000);
  d: path("M12.445 5.778a.889.889 0 1 0 0-1.778a.889.889 0 0 0 0 1.778M9.778 7.4v1.2c0 .16.138.29.311.29h1.445c1.08 0 1.8.635 1.8 1.644v.577h-1.245a3.6 3.6 0 0 0-3.644 3.556c0 1.964 1.63 3.555 3.644 3.555h1.378a.306.306 0 0 0 .311-.31v-2.934a.32.32 0 0 0-.324-.311h-1.698c-.111 0-.2.098-.2.213v.907c0 .115.089.213.2.213h.689v.445h-.396a1.805 1.805 0 0 1-1.69-1.088a1.8 1.8 0 0 1-.15-.69c0-.978.827-1.778 1.84-1.778h2.81c.137 0 .253-.124.253-.275v-2.125c0-1.853-1.614-3.378-3.6-3.378h-1.423c-.173 0-.31.134-.31.29");
}

</style>
