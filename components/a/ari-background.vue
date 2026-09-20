<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="em-nybp0c"/><circle class="bk8q-x_pi"/><path class="c5x69nlfx"/><path clip-rule="evenodd" class="pztiu9b5u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ari-background" /></template>
<style>
.bk8q-x_pi {
  cx: 12px;
  cy: 12px;
  r: 8px;
  fill: var(--svg-color--fff, #fff);
}

.c5x69nlfx {
  fill: var(--svg-color--202451, #202451);
  d: path("M7.968 13.37a.09.09 0 0 0 .087-.046l1.248-2.376a.092.092 0 0 1 .164 0l1.248 2.377a.1.1 0 0 0 .087.046h.32a.094.094 0 0 0 .082-.137l-1.586-3.017a.09.09 0 0 0-.082-.046h-.302a.09.09 0 0 0-.082.046l-1.586 3.017a.094.094 0 0 0 .087.137h.32zm5.531-3.199h-1.737a.09.09 0 0 0-.091.092v3.016c0 .05.04.092.091.092h.274c.05 0 .092-.041.092-.092v-2.65h1.371c.224 0 .457.264.457.456q-.002.459-.457.457h-.622a.09.09 0 0 0-.091.092v.333c0 .019.01.042.023.06l1.079 1.312a.1.1 0 0 0 .068.032h.366c.078 0 .119-.092.073-.146l-.95-1.226c.539 0 .968-.36.968-.914c0-.48-.457-.914-.914-.914m1.92 3.2a.09.09 0 0 1-.091-.092v-3.016c0-.05.04-.092.09-.092h.275c.05 0 .091.041.091.092v3.016a.09.09 0 0 1-.09.092z");
}

.em-nybp0c {
  fill: var(--svg-color--febb02, #febb02);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pztiu9b5u {
  fill: var(--svg-color--febb02, #febb02);
  fill-rule: evenodd;
  d: path("M12 18.222a6.222 6.222 0 1 0 0-12.444a6.222 6.222 0 0 0 0 12.444m0 .89a7.111 7.111 0 1 0 0-14.223a7.111 7.111 0 0 0 0 14.222");
}

</style>
