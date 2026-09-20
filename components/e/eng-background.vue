<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="n7vh5ebvf"/><path class="ow9crqb2m"/><path class="xf4s4kbfi"/><path class="mxrqhg_cg"/><path class="s22br2gsx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eng-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.mxrqhg_cg {
  fill: var(--svg-color--e82e9d, #e82e9d);
  d: path("m12 7.53l3.678 2.281L12 11.854L8.358 9.812z");
}

.n7vh5ebvf {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.975 4l6.915 3.968v7.936l-6.915 3.968l-6.865-3.968V7.968z");
}

.ow9crqb2m {
  fill: var(--svg-color--065198, #065198);
  d: path("M11.972 11.89L8.326 9.797v4.008l3.646 2.346z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s22br2gsx {
  fill: var(--svg-color--0c0e15, #0c0e15);
  d: path("M4.84 7.7a.243.243 0 0 0 .088.334l6.831 3.976v7.746a.244.244 0 0 0 .487 0V12.01l6.822-3.96a.24.24 0 0 0 .092-.335a.243.243 0 0 0-.337-.086l-6.82 3.96l-6.83-3.976a.243.243 0 0 0-.333.088M12 6.021a.392.392 0 1 0 0-.783a.392.392 0 0 0 0 .783m0 1.074a.392.392 0 1 0 0-.784a.392.392 0 0 0 0 .784m-4.474 7.564a.392.392 0 1 0 0-.784a.392.392 0 0 0 0 .784m-1.074.671a.392.392 0 1 0 0-.783a.392.392 0 0 0 0 .784m10.096-.672a.392.392 0 1 1 0-.784a.392.392 0 0 1 0 .784m1.074.671a.392.392 0 1 1 0-.783a.392.392 0 0 1 0 .784");
}

.xf4s4kbfi {
  fill: var(--svg-color--21b1f8, #21b1f8);
  d: path("m12 12.07l3.674-2.104v4.028L12 16.277z");
}

</style>
