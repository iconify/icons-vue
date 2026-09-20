<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mgf4h9bak"/><path class="r_4kb7g2j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:krl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mgf4h9bak {
  fill: var(--svg-color--5b4a84, #5b4a84);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r_4kb7g2j {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.23 12.205h-.762l.377-1.23h.386V9.578h1.23v2.298l1.642-1.313h1.23v.41l-1.776 1.539l1.776 1.772v.381h-1.23l-1.157-1.21l-.484.353v.857H5.23v-.82H4l.377-1.23h.854zm7.496-.41v-1.231h-.611c-.402 0-.915.193-1.14.624v-.624H9.743v4.102h1.23v-2.153c.005-.768.796-.718 1.752-.718m.907 3.692c1.05-.344 1.612-.948 2.084-1.867c.2-.381.336-.861.525-1.378c-1.28 1.19-1.136 1.19-2.995 2.244zm1.239-2.917l-.616-2.006h-1.23c.151.381 1.017 2.987 1.017 3.122c1.37-.476 2.203-1.608 2.224-1.62c.155-.444.3-1.01.45-1.502h-1.23c-.21.78-.357 1.444-.615 2.006m2.256-2.827h1.231v4.923h-1.23zm1.641-1.23H20v6.153h-1.23z");
}

</style>
