<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="lrb53vbff"/><path class="cqc__gmgi"/><path class="lhv4o8bzg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bzr-background" /></template>
<style>
.cqc__gmgi {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.554 13.792c0 .178.066.658.102.875c3.302-1.724 5.16-3.675 5.676-4.435c-.165-.045-.533-.2-.693-.454c-1.92 2.383-4.623 3.787-5.085 4.014m.668-7.57a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222m0 13.778a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222M6 16.446a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222m0-6.667a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222m12 0a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222m0 6.667a1.111 1.111 0 1 0 0-2.222a1.111 1.111 0 0 0 0 2.222");
}

.ft5dv1b6b {
  fill: none;
}

.lhv4o8bzg {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.777 11.993c0 2.733.658 5 .983 5.787c.178-.116.59-.347.795-.347c-.733-1.951-.889-4.427-.889-5.431s.156-3.48.89-5.432c-.205 0-.614-.23-.796-.346c-.325.786-.978 3.04-.983 5.769");
}

.lrb53vbff {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.777 9.023c-.298-.156-1.538-.449-2.125-.578c0 .178-.017.574-.097.77c.706.11 1.698.421 2.106.564c.04-.16.116-.534.116-.756m0 5.956c-.298.155-1.538.449-2.125.578c0-.178-.017-.574-.097-.77c.706-.11 1.698-.422 2.106-.564c.04.16.116.534.116.756m7.111-7.716l-3.133-1.929c-.068.268-.215.51-.422.693c.973.605 2.973 1.84 3.173 1.974c.044-.29.276-.614.382-.738m0 9.476l-3.133 1.929a1.4 1.4 0 0 0-.422-.694c.973-.604 2.973-1.84 3.173-1.973c.044.289.276.613.382.738m-5.333-6.085c0-.178.066-.658.102-.875c3.302 1.724 5.16 3.675 5.676 4.435c-.165.045-.534.2-.694.454c-1.92-2.383-4.622-3.787-5.084-4.014");
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
