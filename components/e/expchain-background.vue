<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i_v3r8bnu"/><path clip-rule="evenodd" class="uin6-601e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:expchain-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i_v3r8bnu {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M0 0h24v24H0z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uin6-601e {
  fill: var(--svg-color--141413, #141413);
  fill-rule: evenodd;
  d: path("m13.302 4.744l5.696 9.767a1.48 1.48 0 0 1-.55 2.034L12.752 19.8a1.52 1.52 0 0 1-1.504 0l-5.696-3.255a1.48 1.48 0 0 1-.55-2.034l5.696-9.767c.578-.992 2.025-.992 2.604 0m-7.2 10.396a.23.23 0 0 0 .085.316l5.49 3.139V5.578zm6.22-9.562v13.017l5.49-3.139a.23.23 0 0 0 .086-.316z");
}

</style>
