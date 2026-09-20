<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="spuoldbhf"><path class="vm72r_nue"/><path class="kc-6j1qsr"/><path class="mx59d-bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitkub-chain" /></template>
<style>
.kc-6j1qsr {
  d: path("M8.761 6.238L7.522 7.472l.008.008l-3.305 3.29v-.006L3 11.982l.005.005l-.005.005l1.211 1.216l4.51 4.554s1.067-1.407.018-2.46l-3.3-3.317l3.303-3.292l1.667 1.678c1.422 1.43 2.436-.032 2.436-.032zm12.223 5.772l.016-.015l-5.702-5.727s-1.047 1.369-.055 2.365l3.367 3.381l-3.296 3.283l-1.542-1.547c-1.105-1.11-2.569-.105-2.569-.105l4.064 4.08l5.726-5.705z");
}

.mx59d-bxr {
  d: path("m14.482 11.164l-.012.012a1.157 1.157 0 0 0-.004 1.636l.013.012c.45.452 1.183.454 1.636.003l.012-.012c.452-.45.454-1.183.003-1.636l-.012-.012a1.157 1.157 0 0 0-1.636-.003");
}

.spuoldbhf {
  fill: var(--svg-color--02d767, #02d767);
}

.vm72r_nue {
  d: path("m7.89 11.164l-.013.012a1.157 1.157 0 0 0-.003 1.636l.012.012c.45.452 1.183.454 1.636.003l.012-.012c.453-.45.454-1.183.003-1.636l-.012-.012a1.157 1.157 0 0 0-1.636-.003");
}

</style>
