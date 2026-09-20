<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eyx1b46bz"/><path class="m7h3neznq"/><path class="wzesg2btv"/><path class="prbjvob9v"/><path class="be4tn-bej"/><circle class="iwvn9uocx"/><circle class="fvoqpqbzu"/><path class="sclegwbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:door" /></template>
<style>
.be4tn-bej {
  fill: var(--svg-color--c87d5e, #c87d5e);
  d: path("m83.63 74.14l-5.1 4.82h.19v28.32H49.65l-5.28 5h39.26z");
}

.eyx1b46bz {
  fill: var(--svg-color--b06542, #b06542);
  d: path("m33.28 123.87l61.43.13c1.22 0 2.2-.89 2.2-1.99V6.12c0-1.1-.98-1.99-2.19-1.99L33.29 4c-1.22 0-2.2.89-2.2 1.99v115.88c0 1.1.98 2 2.19 2");
}

.fvoqpqbzu {
  cx: 82.61px;
  cy: 64.45px;
  r: 5.25px;
  fill: var(--svg-color--bdbdbd, #bdbdbd);
}

.iwvn9uocx {
  cx: 84.65px;
  cy: 66px;
  r: 5.25px;
  fill: var(--svg-color--874d36, #874d36);
}

.m7h3neznq {
  fill: var(--svg-color--874d36, #874d36);
  d: path("M78.72 20.72v30.32H49.28V20.72zm4.91-5H44.37v40.32h39.26z");
}

.prbjvob9v {
  fill: var(--svg-color--874d36, #874d36);
  d: path("M78.72 78.96v28.32H49.28V78.96zm4.91-5H44.37v38.32h39.26z");
}

.sclegwbkg {
  fill: var(--svg-color--eee, #eee);
  d: path("M83.85 61.11c.13.65-.25.97-.79 1.36s-1.21.7-1.7 1.53c-.35.59-.46 1.37-1.03 1.76c-.56.38-1.2.31-1.5-.36c-.43-.95-.44-2.6.77-3.95c1.16-1.29 3.93-1.98 4.25-.34");
}

.wzesg2btv {
  fill: var(--svg-color--c87d5e, #c87d5e);
  d: path("m83.63 15.9l-5.1 4.82h.19v30.32H49.65l-5.28 5h39.26z");
}

</style>
