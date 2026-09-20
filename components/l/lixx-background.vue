<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u7-ogvbpa"/><path class="zf3z5l6ux"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lixx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u7-ogvbpa {
  fill: var(--svg-color--e47a04, #e47a04);
  d: path("M24 0H0v24h24z");
}

.zf3z5l6ux {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.974 8.3l.41-1.428l.41 1.428l-.41 1.034zM20 9.333h-1.686l-1.596 2.548l-1.596-2.548h-1.686l2.437 3.897l-2.437 3.898h1.686l1.596-2.548l1.596 2.548H20l-2.437-3.898zM9.744 8.103c.287.024.927.307 1.23 1.23c-.188-.119-1.042-.197-1.23-1.23m3.282 0c-.287.024-.928.307-1.231 1.23c.189-.119 1.042-.197 1.23-1.23m-7.384 1.23H4v7.795h5.333v-1.641H5.641zm4.328 2.613l-.193-.594a.65.65 0 0 1 .07-.554c.193-.312.435-.71.579-.956a.21.21 0 0 1 .246-.086c.307.098.615.147.714.16c.094-.013.406-.062.71-.165c.094-.028.204.009.245.09l.378.616l-1.288.246l1.58.308c.024.11.02.23-.017.34l-.804 2.478l-1.038.206l.915.172l-.681 2.1l-1.21-3.729l1.538-.295zm-.225 4.977l1.64-.205l1.642.205l-1.641.205z");
}

</style>
