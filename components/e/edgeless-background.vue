<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="hr1fi-b8a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:edgeless-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hr1fi-b8a {
  fill: var(--svg-color--a0eb67, #a0eb67);
  fill-rule: evenodd;
  d: path("M4.838 4.022c-.06.055-.045 14.46.016 14.478c.029.01.463.01.964.002l.91-.014l-.013-7.236l-.013-7.236l-.914-.014c-.502-.007-.93.002-.95.02m4.248.485c-.622.01-.894.03-.924.072c-.05.07-.047 4.821.004 4.819c.019-.001.146-.168.283-.371c.264-.392.678-.872.751-.872c.024 0 .044 1.626.044 3.613c0 2.183-.02 3.614-.05 3.614c-.065 0-.648-.695-.842-1.002c-.083-.134-.165-.243-.18-.243c-.017 0-.029 1.093-.027 2.43l.002 2.428l.943.013c.867.012.946.006.965-.072c.047-.186.008-14.375-.039-14.407c-.027-.02-.446-.029-.93-.022m2.444.52c-.043.038-.052 1.74-.01 1.74c.015 0 .201-.043.414-.095c.464-.115.629-.122.63-.024l.001 5.18c0 4.354-.01 5.111-.075 5.124c-.041.007-.268-.03-.505-.084a9 9 0 0 0-.462-.098c-.018 0-.026.619-.018 1.375l.014 1.376h1.874v-14.5l-.913-.014c-.503-.007-.93.002-.95.02m3.293 1.054l.015.558l.429.129c.48.144.906.327 1.244.535l.228.139v8.651l-.148.093c-.25.159-.92.448-1.346.582l-.407.127V20h1.874l.014-1.945l.014-1.945l.36-.274c.443-.335.93-.818 1.181-1.168c.287-.402.632-1.087.762-1.512c.149-.49.209-1.82.105-2.34c-.223-1.121-.99-2.33-1.918-3.023c-.196-.147-.387-.314-.424-.371c-.046-.072-.066-.379-.067-1.002v-.897h-1.931z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
