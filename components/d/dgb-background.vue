<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iffakcc6p"/><path class="vth0gccdw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dgb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iffakcc6p {
  fill: var(--svg-color--006ad2, #006ad2);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vth0gccdw {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.348 20l.459-1.245l-.744.07l-.327.834c-.072.162-.142.332-.35.332L5.68 20l.355-1H4.15c.008-.123 3.616-9.228 3.756-9.5h3.07c.28.027.438.243.35.523l-.428 1.103l-1.855 4.96c2.571 0 5.004-1.508 6.107-3.84C15.982 10.672 16.21 8 13.759 8H4.126l1.269-2.116a.67.67 0 0 1 .612-.368h5.127L11.712 4h1.68a.186.186 0 0 1 .158.219l-.044.14l-.377 1l-.053.15h.7l.053-.114l.491-1.273C14.363 4 14.363 4 14.477 4h1.487c.202 0 .28.114.202.315l-.404 1.089l-.061.148l.131.027c.683.087 1.356.236 1.986.525c.481.219.919.499 1.277.901c.49.543.735 1.181.77 1.907c.044.7-.087 1.382-.323 2.039a11.45 11.45 0 0 1-2.476 4.156c-1.633 1.687-3.799 2.69-6.055 3.245c-.105.027-.157.07-.192.175l-.442 1.184c-.087.219-.175.289-.393.289z");
}

</style>
