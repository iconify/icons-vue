<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nuytl1b8l"/><path class="lkvrdi83d"/><path class="dwgj0-buu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lisk-background" /></template>
<style>
.dwgj0-buu {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.606 17.619l-2.088 2.346l-.025.018l-.023.017H9.157c-.024 0-.036-.012-.047-.024l-3.87-4.351a.08.08 0 0 1 0-.07l4.82-8.283c.024-.035.082-.035.106 0l1.349 2.324c.011.01.011.034 0 .058l-3.261 5.595c-.012.023 0 .047.011.07l1.948 2.182a.1.1 0 0 0 .047.024h2.299c.058 0 .082.058.047.094");
}

.ft5dv1b6b {
  fill: none;
}

.lkvrdi83d {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.589 6.358l1.36-2.323c.024-.047.083-.047.094 0l6.722 11.496c.011.023 0 .046-.012.07l-3.87 4.352a.1.1 0 0 1-.048.024h-3.144c-.058 0-.082-.059-.047-.094l2.1-2.37l1.971-2.205c.024-.023.024-.047.012-.07l-5.138-8.822c-.012-.011-.012-.035 0-.058");
}

.nuytl1b8l {
  fill: var(--svg-color--0c152e, #0c152e);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
