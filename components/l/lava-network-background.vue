<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zk5829bou"/><path class="l8_4_bcqp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lava-network-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l8_4_bcqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.002 19.2L4 15.216L7.66 9.69L10.9 4.8h2.2l3.24 4.89L20 15.216L12 19.2zm.159-11.87a.38.38 0 0 0 .213.342l2.996 1.471c.029.015.058-.018.041-.046l-2.553-3.853h-.697zm6.907 7.854l.282-.14l-2.887-4.358c-.017-.026-.058-.014-.058.017v2.98c0 .118.067.225.173.277zm-11.465-1.38L5.027 15.07a.158.158 0 0 0 0 .284l.143.071a.48.48 0 0 0 .43 0l2.212-1.086l4.196 2.061l4.233-2.08a.23.23 0 0 0 0-.414l-.175-.086a.13.13 0 0 1-.07-.114V9.91L12.23 8.06a.13.13 0 0 1-.07-.113v-.149a.156.156 0 0 0-.227-.138L7.95 9.618a.62.62 0 0 0-.347.554zm.474-3.723v3.485l3.667-1.802V8.28zM12 15.83l3.62-1.778L12 12.275l-3.62 1.778z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zk5829bou {
  fill: var(--svg-color--d7001f, #d7001f);
  d: path("M24 0H0v24h24z");
}

</style>
