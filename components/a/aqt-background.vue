<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="by4iwcb4a"/><path clip-rule="evenodd" class="tydxq6ktb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aqt-background" /></template>
<style>
.by4iwcb4a {
  fill: var(--svg-color--fc452d, #fc452d);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tydxq6ktb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.634 18.58c.315.533 0 1.42-.568 1.42c-.664 0-.805-.175-.965-.373l-.092-.107l-2.725-5.373a3.67 3.67 0 0 0-3.346-1.702c-2.328.121-3.186 1.246-4.258 3.583v.156a8 8 0 0 1 2.105-.228c1.469 0 3.816 1.047 4.427 2.681c.145.388.005.844-.228 1.028c-.29.238-.757.432-1.3.068c-.13-.087-.261-.247-.421-.441c-.51-.616-1.28-1.557-3.104-1.435c-1.906.13-2.968 1.26-3.259 1.808a.97.97 0 0 1-.911.316c-.573-.112-.849-.529-.713-1.106c.077-.31 2.376-5.063 4.607-9.694L11.18 4.43a.762.762 0 0 1 1.363-.015l7.09 14.16zm-9.466-7.629l1.755-3.806l1.78 3.806c-.427-.136-1.736-.33-3.535 0");
}

</style>
