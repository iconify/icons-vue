<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dklyl40xv"/><path fill="url(#SVGwZIvEejJ)" clip-rule="evenodd" class="frmcr_bou"/><path class="v_vykh7iv"/><path class="g42urvhbk"/><path class="jgdsabc-x"/><path clip-rule="evenodd" class="uzrn6f27t"/><defs><linearGradient id="SVGwZIvEejJ" x1="14.058" x2="5.645" y1="1.254" y2="20.342" gradientUnits="userSpaceOnUse"><stop class="hmfiphj9y"/><stop offset="1" class="ht8zy-hyf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fida" /></template>
<style>
.dklyl40xv {
  fill: var(--svg-color--5f60c7, #5f60c7);
  d: path("M11.777 3.313h.46v4.12h-.46zM7.803 14.098l.241.394l-3.481 2.084l-.237-.389zm8.46.072l-.237.393l3.534 2.117l.236-.388z");
}

.frmcr_bou {
  fill-rule: evenodd;
  d: path("M7.737 9.645L12 7.263l4.263 2.382v4.713L12 16.736l-4.263-2.378zm.473.209L12 7.736l3.79 2.118v4.187l-3.785 2.222L8.21 14.04z");
}

.ft5dv1b6b {
  fill: none;
}

.g42urvhbk {
  fill: var(--svg-color--8081ee, #8081ee);
  d: path("m12.284 11.862l-.237.389l-7.82-4.477l.236-.388z");
}

.hmfiphj9y {
  stop-color: var(--svg-color--86e0e9, #86e0e9);
}

.ht8zy-hyf {
  stop-color: var(--svg-color--259ac1, #259ac1);
}

.jgdsabc-x {
  fill: var(--svg-color--8081ee, #8081ee);
  d: path("m11.763 11.862l.237.389l7.816-4.477l-.237-.388z");
}

.uzrn6f27t {
  fill: var(--svg-color--8081ee, #8081ee);
  fill-rule: evenodd;
  d: path("M3.947 7.524L12 3l8.053 4.524v8.957L12 21l-8.053-4.519zm.474.213L12 3.474l7.579 4.263v8.526L12 20.526l-7.579-4.263z");
}

.v_vykh7iv {
  fill: var(--svg-color--8081ee, #8081ee);
  d: path("M11.768 11.863h.459v9h-.46z");
}

</style>
