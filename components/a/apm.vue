<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGHG8hkboF)" class="pmberhbfn"/><defs><linearGradient id="SVGHG8hkboF" x1="7.055" x2="25.788" y1="6.122" y2="24.95" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apm" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.pmberhbfn {
  d: path("M13.841 13.132c-.514.64-1.599 1.109-2.403 1.109c-.774 0-1.688-.4-1.688-1.334c0-.89.74-1.21 1.488-1.362c.88-.183 2.193-.291 3.012-.688c0 .744.065 1.634-.409 2.275m-1.84-7.252c1.413 0 2.25.44 2.25 1.446c0 1.106-1.667 1.135-2.459 1.191c-1.728.221-3.064.379-3.944.6c-.913.189-1.63.44-2.12.82c-1.035.668-1.597 1.946-1.597 3.152c-.064 1.104.327 2.05 1.142 2.806c.814.789 2.053 1.168 3.78 1.168c1.043 0 1.924-.158 2.738-.442a7.7 7.7 0 0 0 2.216-1.356l.243 1.797h5.625c-.49-.347-.562-1.45-.562-2.05V8.235C19.313 4.168 16.108 3 12.28 3c-3.246 0-7.292.721-7.592 4.5H9.75c.085-1.055.836-1.62 2.25-1.62m7.312 13.433H4.688V21h14.625z");
}

</style>
