<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="pl-waga3b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fxs-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pl-waga3b {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.155 5.029a53 53 0 0 0-.962 1.031c0 .011.468.484 1.048 1.037l.376.36l.618.602a6.95 6.95 0 0 0-.107 7.726a85 85 0 0 1-.962 1.02L4.048 18L4 18.052c0 .011 1.784 1.752 1.95 1.892l.065.053l1.01-1.058l1.074-1.14a6.95 6.95 0 0 0 7.748.033c.478.467 2.203 2.128 2.224 2.138c.016.006 1.934-2.014 1.929-2.041c-.006-.016-1.322-1.29-2.122-2.053l-.038-.037a6.95 6.95 0 0 0-.01-7.683l.961-1.021q.572-.585 1.112-1.198a68 68 0 0 0-2.01-1.918c-.015 0-.51.505-1.095 1.128c-.414.44-.78.827-.967 1.016a6.95 6.95 0 0 0-7.565-.065l-.032-.032l-.376-.36l-.591-.57l-.973-.94l-.193-.193l-.946 1.02zM12 16.3a4.298 4.298 0 1 0 0-8.596a4.298 4.298 0 0 0 0 8.596");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
