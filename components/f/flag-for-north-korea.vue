<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x79zls0lr"/><path class="o-j9y7s6b"/><g class="n1mjunbsu"><path class="c333i0ovs"/><circle class="fldm03blg"/></g><path class="cpumhob2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-north-korea" /></template>
<style>
.c333i0ovs {
  d: path("M5 45c.7 1.4 1.5 2.7 2.3 4h49.4c.9-1.3 1.7-2.6 2.3-4zm54-26c-.7-1.4-1.5-2.7-2.3-4H7.3c-.9 1.3-1.7 2.6-2.3 4z");
}

.cpumhob2f {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("m18 35.9l4.9 3.8l-1.8-6.1l4.9-3.8h-6.1L18 23.7l-1.9 6.1H10l4.9 3.8l-1.8 6.1z");
}

.fldm03blg {
  cx: 18px;
  cy: 32px;
  r: 11px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o-j9y7s6b {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M59 19H5c-1.9 3.9-3 8.3-3 13s1.1 9.1 3 13h54c1.9-3.9 3-8.3 3-13s-1.1-9.1-3-13");
}

.x79zls0lr {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C21.7 2 12.7 7.1 7.3 15h49.4C51.3 7.1 42.3 2 32 2m0 60c10.3 0 19.3-5.1 24.7-13H7.3c5.4 7.9 14.4 13 24.7 13");
}

</style>
