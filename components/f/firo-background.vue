<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f4ko4ot6w"/><path class="wp8m9wbey"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:firo-background" /></template>
<style>
.f4ko4ot6w {
  fill: var(--svg-color--8d1b28, #8d1b28);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wp8m9wbey {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.002 19.999a7.993 7.993 0 0 0 7.415-10.993h-3.893a.5.5 0 0 0-.434.255l-.69 1.244h1.599a.5.5 0 0 1 .5.5v1.499a.5.5 0 0 1-.5.5H13l-2.373 4.242a.5.5 0 0 1-.435.254H6.196a7.97 7.97 0 0 0 5.806 2.5m-7.415-4.997a7.994 7.994 0 0 1 13.22-8.494H14.06a.5.5 0 0 0-.434.255l-2.094 3.742H8.504a.5.5 0 0 0-.5.5v1.499a.5.5 0 0 0 .5.5h1.634l-.974 1.743a.5.5 0 0 1-.435.255z");
}

</style>
