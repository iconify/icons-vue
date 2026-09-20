<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pc8z-ib3j"/><path clip-rule="evenodd" class="y47_wrbnx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hns-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pc8z-ib3j {
  fill: var(--svg-color--0e3ca5, #0e3ca5);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y47_wrbnx {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m17.725 9.219l-.994-1.766h1.926c.051 0 .111.035.14.08l1.023 1.685zm-3.563 10.697c-.047.084-.107.084-.127.084h-1.97l3.06-5.495a.295.295 0 0 0-.255-.439l-5.217.007l-1.037-1.796h7.602l.012-.001a.3.3 0 0 0 .087-.019l.02-.008a.3.3 0 0 0 .139-.126l1.252-2.315h2.068zm-2.607-.208l-1.014-1.671c-.016-.025-.023-.086.01-.143l1.795-3.235l2.023-.003zm-3.449-3.44l-1.005-1.785l1.013-1.9l1.016 1.76c-.315.595-.808 1.522-1.024 1.926m-1.35.279H5.662a.18.18 0 0 1-.138-.08l-.328-.54l-.695-1.146h2.094l.994 1.766zm3.401-12.463C10.204 4 10.264 4 10.284 4h1.978L9.193 9.495l-.006.014a.3.3 0 0 0-.026.083l-.004.033l-.001.015l.001.01a.2.2 0 0 0 .008.059l.009.027l.01.027l.013.025l.015.023l.019.022l.019.021l.021.017l.025.018l.01.007l.01.004a.3.3 0 0 0 .048.02l.018.005a.3.3 0 0 0 .067.008h.132l5.086-.006c.135.234.386.674.6 1.049l.407.712H8.107l-.01.002a.29.29 0 0 0-.255.154L6.59 14.192H4.524c.901-1.619 5.573-10 5.633-10.108m2.611.215l.184.303l.826 1.361c.016.025.023.085-.01.143l-1.796 3.235l-2.021.003zm3.444 3.43l1.006 1.787l-1.025 1.896l-1.02-1.782c.22-.4.797-1.46 1.04-1.9");
}

</style>
