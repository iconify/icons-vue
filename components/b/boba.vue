<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ehosi5bwm"/><path class="nhs6h7ewl"/><path class="i2l1kqn_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:boba" /></template>
<style>
.ehosi5bwm {
  fill: var(--svg-color--aedb01, #aedb01);
  d: path("M12.05 14.999H3.841V3h8.207a5.1 5.1 0 0 1 5.097 5.102v1.795a5.1 5.1 0 0 1-5.097 5.102");
}

.ft5dv1b6b {
  fill: none;
}

.i2l1kqn_b {
  fill: var(--svg-color--5d6d3c, #5d6d3c);
  d: path("M17.146 9.794v.102a5.1 5.1 0 0 1-5.102 5.102H3.842A5.997 5.997 0 0 1 9.839 9h4.32c1.091 0 2.11.293 2.987.793");
}

.nhs6h7ewl {
  fill: var(--svg-color--b0b1ac, #b0b1ac);
  d: path("M14.159 21H3.842v-6.002A5.995 5.995 0 0 1 9.839 9h4.32a6 6 0 1 1 0 11.999");
}

</style>
