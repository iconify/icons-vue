<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nu6v52bsv"/><path class="fkc73stqp"/><path class="btulgcfzf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btcp-background" /></template>
<style>
.btulgcfzf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.172 16.082a1.604 1.604 0 0 0 1.635-2.59c1.088-.002 1.429-.134 2.046-.374l.194-.075c.653.78.932 1.819.66 2.831c-.44 1.642-2.61 2.5-4.37 2.143l-.001.007l-.885-.238L11.857 20l-1.328-.356l1.068-3.984z");
}

.fkc73stqp {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.349 4l-.593 2.214l-3.099-.83l-.475 1.77l1.328.356a.46.46 0 0 1 .324.561l-1.66 6.198a.46.46 0 0 1-.561.324l-.886-.238l-.917 1.652l3.099.831l-.593 2.214l1.328.355l1.897-7.083l1.55.415c1.74.466 4.498.035 5.036-1.972c.436-1.627-1.502-3.25-2.83-3.605l.593-2.213l-1.328-.356l-.593 2.214l-.885-.238l.593-2.213zm.26 4.34l1.796.481a1.375 1.375 0 1 1-.712 2.656l-1.795-.481z");
}

.ft5dv1b6b {
  fill: none;
}

.nu6v52bsv {
  fill: var(--svg-color--272d63, #272d63);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
