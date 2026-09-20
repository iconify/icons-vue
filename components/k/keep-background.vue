<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cf1clxb7v"/><path clip-rule="evenodd" class="rnyilgbus"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:keep-background" /></template>
<style>
.cf1clxb7v {
  fill: var(--svg-color--49dbb4, #49dbb4);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rnyilgbus {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a7.999 7.999 0 1 0 0-15.998A7.999 7.999 0 0 0 12 20M9.333 8.444h-.889v1.778h.445v3.556h-.445v1.778h3.112v-1.778h-.445v-1.111h.529l.898 1.11h-.094v1.779h3.112v-1.778h-.56l-1.547-1.787l1.498-1.769h.609V8.444h-3.111v1.778h.133l-1.005 1.111h-.462v-1.11h.445v-1.78h-.89v.445h-.444v-.445h-.444v.445h-.445z");
}

</style>
