<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dgslsnb2f"/><path class="ppa3odb7x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hot-background" /></template>
<style>
.dgslsnb2f {
  fill: var(--svg-color--007f88, #007f88);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ppa3odb7x {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.415 6.218s-.431.014-.415.039c.09.248.688 1.611.696 1.62c2.154.171 3.64 1.072 4.403 3.155h-1.22l-.735 1.94s1.757-.003 1.955 0c-.61 1.951-2.314 3.093-4.33 3.093c-.085.202-.708 1.65-.678 1.66c3.49.404 6.783-2.172 7.103-4.754h1.555c0 .331.256.936.442 1.334c1.13 2.275 3.574 3.579 6.073 3.511c.409-.008.72-.058.703-.1l-.695-1.61c-1.967-.156-4.157-.944-4.592-3.135h1.222c.017 0 .674-1.939.674-1.939h-1.912c.68-2.06 2.531-3.117 4.657-3.147c0 0 .47-1.062.679-1.603c-3.153-.591-6.722 1.494-7.259 4.75H11.22c-.385-3.401-4.076-4.954-6.804-4.814");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
